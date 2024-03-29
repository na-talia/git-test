Git Commands
git config
Usage: git config –global user.name “[name]”  

Usage: git config –global user.email “[email address]”  

This command sets the author name and email address respectively to be used with your commits.

Git Config Command - Git Commands 
git init

Usage: git init [repository name]

 

This command is used to start a new repository.

GitInit Command - Git Commands 
git clone

Usage: git clone [url]  

This command is used to obtain a repository from an existing URL.

Git Clone Command - Git Commands
git add

Usage: git add [file]  

This command adds a file to the staging area.

Git Add Command - Git Commands 

Usage: git add *  

This command adds one or more to the staging area.

Git Add Command - Git Commands 
git commit

Usage: git commit -m “[ Type in the commit message]”  

This command records or snapshots the file permanently in the version history.

Git Commit Command - Git Commands 

Usage: git commit -a  

This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.

Git Commit Command - Git Commands 
git diff

Usage: git diff  

This command shows the file differences which are not yet staged.

Git Diff Command - Git Commands 

 Usage: git diff –staged 

This command shows the differences between the files in the staging area and the latest version present.

Git Diff Command - Git Commands 

Usage: git diff [first branch] [second branch]  

This command shows the differences between the two branches mentioned.

Git Diff Command - Git Commands
git reset

Usage: git reset [file]  

This command unstages the file, but it preserves the file contents.

Git Reset Command - Git Commands

Usage: git reset [commit]  

This command undoes all the commits after the specified commit and preserves the changes locally.

Git Reset Command - Git Commands

Usage: git reset –hard [commit]  This command discards all history and goes back to the specified commit.

Git Reset Command - Git Commands
git status

Usage: git status  

This command lists all the files that have to be committed.

Git Status Command - Git Commands
git rm

Usage: git rm [file]  

This command deletes the file from your working directory and stages the deletion.

Git Rm Command - Git Commands
git log

Usage: git log  

This command is used to list the version history for the current branch.

Git Log Command - Git Commands

Usage: git log –follow[file]  

This command lists version history for a file, including the renaming of files also.

Git Log Command - Git Commands
git show

Usage: git show [commit]  

This command shows the metadata and content changes of the specified commit.

Git Show Command - Git Commands
git tag

Usage: git tag [commitID]  

This command is used to give tags to the specified commit.

Git Tag Command - Git Commands
git branch

Usage: git branch  

This command lists all the local branches in the current repository.

Git Branch Command - Git Commands

Usage: git branch [branch name]  

This command creates a new branch.

Git Branch Command - Git Commands

Usage: git branch -d [branch name]  

This command deletes the feature branch.

Git Branch Command - Git Commands
git checkout

Usage: git checkout [branch name]  

This command is used to switch from one branch to another.

Git Checkout Command - Git Commands

Usage: git checkout -b [branch name]  

This command creates a new branch and also switches to it.

Git Checkout Command - Git Commands
git merge

Usage: git merge [branch name]  

This command merges the specified branch’s history into the current branch.

Git Merge Command - Git Commands
git remote

Usage: git remote add [variable name] [Remote Server Link]  

This command is used to connect your local repository to the remote server.

Git Remote Command - Git Commands 
git push

Usage: git push [variable name] master  

This command sends the committed changes of master branch to your remote repository.

Git Push Command - Git Commands 

Usage: git push [variable name] [branch]  

This command sends the branch commits to your remote repository.

Git Push Command - Git Commands 

Usage: git push –all [variable name]  

This command pushes all branches to your remote repository.

Git Push Command - Git Commands

Usage: git push [variable name] :[branch name]  

This command deletes a branch on your remote repository.

Git Push Command - Git Commands 
git pull

Usage: git pull [Repository Link]  

This command fetches and merges changes on the remote server to your working directory.

Git Pull Command - Git Commands
git stash

Usage: git stash save  

This command temporarily stores all the modified tracked files.

Git Stash Command - Git Commands

Usage: git stash pop  

This command restores the most recently stashed files.

Git Stash Command - Git Commands

Usage: git stash list  

This command lists all stashed changesets.

Git Stash Command - Git Commands

Usage: git stash drop  

This command discards the most recently stashed changeset.

Git Stash Command - Git Commands

