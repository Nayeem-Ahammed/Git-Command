# Git Command Cheat Sheet

## Configuration
- `git config --global user.name "Your Name"`: Set the name that will be attached to your commits.
- `git config --global user.email "your.email@example.com"`: Set the email that will be attached to your commits.
- `git config --list`: List all configuration settings.

## Creating Repositories
- `git init`: Initialize a new Git repository.
- `git clone <repository>`: Clone an existing repository.

## Basic Snapshotting
- `git add <file>`: Add a file to the staging area.
- `git add .`: Add all files to the staging area.
- `git commit -m "commit message"`: Commit the staged changes with a message.
- `git status`: Show the status of the working directory and staging area.
- `git log`: Show the commit history.

## Branching and Merging
- `git branch`: List all branches.
- `git branch <branch-name>`: Create a new branch.
- `git checkout <branch-name>`: Switch to a branch.
- `git merge <branch-name>`: Merge a branch into the current branch.
- `git branch -d <branch-name>`: Delete a branch.

## Remote Repositories
- `git remote -v`: List all configured remote repositories.
- `git remote add <name> <url>`: Add a new remote repository.
- `git fetch <remote>`: Fetch changes from a remote repository.
- `git pull <remote> <branch>`: Pull changes from a remote repository.
- `git push <remote> <branch>`: Push changes to a remote repository.

## Undoing Changes
- `git reset <file>`: Unstage a file.
- `git reset --hard`: Reset the working directory and staging area to the last commit.
- `git revert <commit>`: Create a new commit that undoes the changes from a previous commit.

## Stashing
- `git stash`: Stash the current changes in the working directory.
- `git stash apply`: Apply the stashed changes.
- `git stash list`: List all stashes.

## Viewing Changes
- `git diff`: Show changes between the working directory and the staging area.
- `git diff <commit>`: Show changes between a commit and the working directory.
- `git diff <commit1> <commit2>`: Show changes between two commits.

## Tagging
- `git tag`: List all tags.
- `git tag <tag-name>`: Create a new tag.
- `git push <remote> <tag-name>`: Push a tag to a remote repository.

## Miscellaneous
- `git help <command>`: Show help for a specific Git command.