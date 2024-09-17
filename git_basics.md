# Basic Git Commands for Beginners

## 1. Setup Commands
- **`git config --global user.name "Your Name"`**  
  Sets the username for your commits.
- **`git config --global user.email "your_email@example.com"`**  
  Sets the email address for your commits.
- **`git config --global color.ui auto`**  
  Enables color-coded Git output to make it easier to read.

## 2. Repository Commands
- **`git init`**  
  Initializes a new Git repository in the current directory.
- **`git clone <repository_url>`**  
  Copies an existing remote repository to your local machine.  
  Example: `git clone https://github.com/user/repo.git`

## 3. Basic Workflow Commands
- **`git status`**  
  Shows the status of your working directory, including changes staged for commit and untracked files.
- **`git add <file>`**  
  Stages a specific file for commit.  
  Example: `git add index.html`
- **`git add .`**  
  Stages all changed files in the current directory.
- **`git commit -m "Commit message"`**  
  Commits staged changes to the local repository with a message describing the changes.
- **`git commit -a -m "Commit message"`**  
  Automatically stages all modified and deleted files, then commits with a message.

## 4. Viewing Changes
- **`git log`**  
  Shows the commit history for the repository.
- **`git log --oneline`**  
  Displays a simplified log with each commit on a single line.
- **`git diff`**  
  Shows differences between the working directory and the staged changes.
- **`git diff <file>`**  
  Shows differences for a specific file.
- **`git diff --staged`**  
  Shows differences between the staged changes and the last commit.

## 5. Branching and Merging
- **`git branch`**  
  Lists all branches in the repository and shows the current branch.
- **`git branch <branch_name>`**  
  Creates a new branch.  
  Example: `git branch feature-branch`
- **`git checkout <branch_name>`**  
  Switches to a specified branch.  
  Example: `git checkout feature-branch`
- **`git checkout -b <branch_name>`**  
  Creates and switches to a new branch.
- **`git merge <branch_name>`**  
  Merges the specified branch into the current branch.
- **`git branch -d <branch_name>`**  
  Deletes a branch after it has been merged.

## 6. Remote Repositories
- **`git remote -v`**  
  Lists all remote repositories associated with the local repository.
- **`git remote add origin <repository_url>`**  
  Adds a remote repository and names it "origin."
- **`git push -u origin <branch_name>`**  
  Pushes the specified branch to the remote repository and sets up tracking.  
  Example: `git push -u origin main`
- **`git push`**  
  Pushes committed changes to the remote repository.
- **`git pull`**  
  Fetches and merges changes from the remote repository into the current branch.
- **`git fetch`**  
  Retrieves changes from the remote repository but does not merge them into the current branch.

## 7. Undoing Changes
- **`git reset <file>`**  
  Unstages a file while keeping the changes in the working directory.
- **`git checkout -- <file>`**  
  Discards changes in the working directory.
- **`git revert <commit>`**  
  Creates a new commit that undoes the changes from a specified commit.
- **`git reset --hard <commit>`**  
  Resets the current branch to the specified commit and discards all changes.

## 8. Miscellaneous Commands
- **`git stash`**  
  Temporarily saves changes that are not ready to be committed.
- **`git stash pop`**  
  Applies stashed changes and removes them from the stash.
- **`git stash list`**  
  Lists all stashed changes.
