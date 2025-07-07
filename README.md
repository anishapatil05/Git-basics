# Git-basics
* This repository contains basic Git commands I used during my learning.

# Git Configuration :
1) git config --global user.name "Your Name"
2) git config --global user.email "your.email@example.com"

 # Basic commands 
 1) git init :  Initialize Git Repository.
 2) git add : adds new or changed files from working directory to stagging area.
 3) git commit : Commit staged changes with a message.
 4) git status : See which files are staged, unstaged, or untracked.
 5) git diff : Show changes in unstaged files.

# Viewing History
 1) git log : To Show commit history.

#  Branching 
 1) git branch : to check branch.
 2) git branch -M main : To rename branch.
 3) git checkout <branch-name> : to navigate.
 4) git checkout -b <branch-name> : to create new branch name.
 5) git branch -d <branch-name> : to delete branch.

# Remove or Untrack 
1) git rm file.txt : Remove file from working directory and staging.
2) git rm --cached file.txt : Untrack file without deleting it.
    

#  Push and Pull
 1) git push origin main : push commits to remote main branch.
 2) git pull origin main :Pull updates from remote main branch.

#  Cloning a Repository 
 1) git clone <repository-URL> : Cloning a repository on our local machine.

# Checking the Status
 1) git status : Displays the state of the code.

# Undoing changes 
  * case 1 : Staged changes
      1) git reset <file-name> : for one file.
      2) git reset : for more than one file
  * case 2 : Commited changes
      1) git reset HEAD~1
  * case 3 : Commited changes for many commits.
      1)  git reset <commit-hash> 
      2)  git reset --hard <commit-hash>

 # Fork 
   fork is a rough copy of repository.
    
