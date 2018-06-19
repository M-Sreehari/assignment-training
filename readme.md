# assignment-training
```sh
Git training for freshers.
```
## Git Commands
* ### git config  
  This command sets the author name and email address respectively to be used with your commits. 
* ### git init  
  This command is used to start a new repository. 
* ### git clone  
  This command is used to obtain a repository from an existing URL. 
* ### git add  
  This command adds a file to the staging area. 
* ### git add *  
  This command adds one or more to the staging area.
* ### git commit  
  This command records or snapshots the file permanently in the version history. 
* ### git diff  
  This command shows the file differences which are not yet staged.  
* ### git reset
  * git reset [file]  
    This command unstages the file, but it preserves the file contents.
  * git reset [commit]   
    This command undoes all the commits after the specified commit and preserves the changes locally. 
  * git reset –hard [commit]  
    This command discards all history and goes back to the specified commit.
* ### git status  
  This command lists all the files that have to be committed. 
* ### git rm
  This command deletes the file from your working directory and stages the deletion.  
* ### git log
  This command is used to list the version history for the current branch.  
* ### git show  
  This command shows the metadata and content changes of the specified commit.  
* ### git tag  
  This command is used to give tags to the specified commit.  
* ### git branch  
  * git branch  
      This command lists all the local branches in the current repository. 
  * git branch [branch name]  
      This command creates a new branch.  
  * git branch -d [branch name]  
      This command deletes the feature branch. 
* ### git checkout  
  * git checkout [branch name]  
    This command is used to switch from one branch to another.  
  * git checkout -b [branch name]  
    This command creates a new branch and also switches to it. 
* ### git merge  
  This command merges the specified branch’s history into the current branch.  
* ### git remote  
  This command is used to connect your local repository to the remote server.  
* ### git push 
  * git push [variable name] master  
    This command sends the committed changes of master branch to your remote repository. 
  * git push [variable name] [branch]  
    This command sends the branch commits to your remote repository.  
  * git push –all [variable name]  
    This command pushes all branches to your remote repository.
  * git push [variable name] :[branch name]  
  This command deletes a branch on your remote repository.
* ### git pull  
  This command fetches and merges changes on the remote server to your working directory. 
* ### git stash  
  * git stash save  
  This command temporarily stores all the modified tracked files.
  * git stash pop  
  This command restores the most recently stashed files.
  * git stash list  
  This command lists all stashed changesets.
  * git stash drop  
  This command discards the most recently stashed changeset.
  
