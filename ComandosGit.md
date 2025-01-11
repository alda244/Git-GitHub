# Git Commands Guide

Author: **Alicia Pereira**

## **Basic Commands**

- **`git status`**: Shows the state of the working directory and staging area.
- **`git diff`**: Displays changes between commits, the working directory, and the index.
- **`git clone <url>`**: Creates a copy of an existing repository.
- **`git remote`**: Manages remote repository connections.
- **`git config`**: Configures user information for commits (username and email).
- **`git commit`**: Records changes to the repository.
- **`git push`**: Uploads local commits to a remote repository.
- **`git pull`**: Fetches and merges changes from a remote repository.

## **Stashing and Resetting**

- **`git stash`**: Temporarily saves changes that are not ready to be committed.
- **`git stash drop`**: Removes the last added stash item.
- **`git reset <file>`**: Unstages a file from the staging area without deleting it from the working directory.
- **`git rm <file>`**: Removes a file from both the staging area and the working directory.

## **Branching and Merging**

- **`git branch`**: Lists, creates, or deletes branches.
- **`git checkout <branch>`**: Switches to a specified branch.
- **`git merge <branch>`**: Merges changes from one branch into the current branch.
- **`git rebase <branch>`**: Reapplies commits on top of another base tip.
- **`git cherry-pick <commit>`**: Applies the changes introduced by a specific commit from one branch to another.

## **Viewing History**

- **`git log`**: Shows the commit history.
- **`git reflog`**: Displays the reference logs, tracking changes to branches and tags.
- **`git show <commit>`**: Displays information about a specific commit.

## **Reverting Changes**

- **`git revert <commit>`**: Creates a new commit that undoes changes from a previous commit.
- **`git reset --hard`**: Resets the working directory and index to the last commit, discarding all changes.

## **Advanced Commands**

- **`git bisect`**: Uses binary search to find the commit that introduced a bug.
- **`git stash apply`**: Applies stashed changes back to the working directory.
- **`git reflog expire`**: Prunes older reflog entries.
- **`git reflog delete`**: Deletes specific entries from the reflog.

## *Used Commands in this repository*

- **`git status`**
- **`git init`**
- **`git add <file>`**
- **`git remote add origin <url>`**
- **`git commit -m "<message>"`**
- **`git stash`**
- **`git stash drop`**
- **`git rm <file>`**
- **`git branch -m "main"`**
- **`git push origin main`**
- **`git branch <branch_name>`**
- **`git checkout <branch_name>`**
- **`git merge <name branch>`**
- **`git log`**
- **`git revert <commit>`**
