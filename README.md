# Git-basics
* This repository contains basic Git commands and notes I used during my learning.

# Git Configuration :
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

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
