# Git Commands Cheat Sheet

## Basic Commands

- `git --version`: Check the version
- `git help`: Get help from git
- `git help commit`: Get help for the commit command
- `git config`: Get information about configuration
- `git config --list`: Check all configurations
- `git config --global user.name "username"`: Configure git user name
- `git config --global user.email "email"`: Configure git user email

## Repository Initialization

- `git init`: Initialize git repository on the local machine
- `git status`: Check changes or status of files in the repository

## Staging Changes

- `git add filename1.txt`: Add only one file
- `git add filename1.txt filename2.txt`: Add multiple files
- `git add .`: Add all files and folders to the staging area

## Committing Changes

- `git commit -a`: Stage and write a commit message in Nano
- `git commit -m "commit message"`: Write a commit message after staging
- `git commit -am "commit message"`: Stage and commit everything in one step

## Viewing History

- `git log`: See the history of the repository
- `git log --oneline`: View history in one line
- `git log -<limit>`: Limit the number of log entries
- `git log --author="name"`: Check changes by a specific user
- `git log --graph`: Visualize the history

## Comparing Changes

- `git diff`: Compare working copy with the repository
- `git diff --staged`: Compare files in the staging area

## Undoing Changes

- `git checkout -- filename`: Retrieve working copy
- `git reset HEAD filename`: Unstage changes
- `git checkout <branch-name> <path to file>`: Checkout file from a different branch
- `git checkout <commit-id> -- <path to file>`: Checkout file from a specific commit

## Remote Repository

- `git remote -v`: View remote repository URLs
- `git remote add <remote name> repository-Url`: Add a new remote
- `git push -u remote master`: Push the files to GitHub

## Deleting and Moving Files

- `git rm filename1`: Delete one tracked file
- `git mv filename1 filename2`: Rename a file
- `git mv filename1 foldername/filename1`: Move file to a folder

## Branching

- `git branch`: List branches
- `git branch branch-name`: Create a branch
- `git checkout branch-name`: Switch to a branch
- `git checkout -b branch-name`: Create and switch to a new branch
- `git merge branch-name`: Merge a branch into the current branch

