- 👋 Hi, I’m @waifuneverdie
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
waifuneverdie/waifuneverdie is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# WaifuNeverDie
This will create a properly formatted README file on GitHub, where the code snippets are clearly separated in code blocks and the repository instructions are easy to follow.

### Instructions to Create:
1. Create a `README.md` file in the root of your Git repository.
2. Copy the markdown above into the `README.md` file.
3. Add, commit, and push the changes to GitHub:
```bash
git add README.md
git commit -m "Add instructions to README"
git push origin main
```
## …or create a new repository on the command line
```bash
echo "# waifuneverdie" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/waifuneverdie/waifuneverdie.git
git push -u origin main
```
## …or push an existing repository from the command line
```bash
git remote add origin https://github.com/waifuneverdie/waifuneverdie.git
git branch -M main
git push -u origin main
```



# Git Commands Overview

This is a list of commonly used Git commands, along with a brief description of each. This will help you understand their purpose and how to use them effectively.

## Setup Commands
1. **`git config --global user.name "Your Name"`**: Sets your Git username.
2. **`git config --global user.email "you@example.com"`**: Sets your Git email address.
3. **`git config --list`**: Lists all current configurations.

## Repository Commands
1. **`git init`**: Initializes a new Git repository in your current directory.
2. **`git clone <repository>`**: Creates a copy of an existing repository.

## Working with Changes
1. **`git status`**: Shows the status of changes, including tracked, untracked, and staged files.
2. **`git add <file>`**: Adds a file to the staging area (to be committed).
3. **`git add .`**: Adds all changes in the current directory to the staging area.
4. **`git commit -m "Commit message"`**: Commits staged changes with a message.
5. **`git commit -a`**: Stages all tracked file changes and commits them in one step.
6. **`git diff`**: Shows the differences between the working directory and the staging area.

## Branching and Merging
1. **`git branch`**: Lists all branches in the repository. The current branch is highlighted.
2. **`git branch <branch-name>`**: Creates a new branch.
3. **`git checkout <branch-name>`**: Switches to a specified branch.
4. **`git checkout -b <branch-name>`**: Creates and switches to a new branch.
5. **`git merge <branch-name>`**: Merges changes from the specified branch into the current branch.
6. **`git branch -d <branch-name>`**: Deletes a branch (after it has been merged).

## Remote Repositories
1. **`git remote add <name> <url>`**: Adds a new remote repository.
2. **`git remote -v`**: Shows the URLs of the remote repositories.
3. **`git remote set-url origin <new-url>`**: Change remote URL
4. **`git push`**: Pushes changes to a remote repository.
5. **`git push origin <branch-name>`**: Pushes a specific branch to the remote repository.
6. **`git pull`**: Fetches and merges changes from the remote repository into the current branch.
7. **`git fetch`**: Fetches changes from the remote but does not merge them.

## Undoing Changes
1. **`git reset <file>`**: Unstages a file that has been added to the staging area.
2. **`git reset --hard`**: Resets the working directory and staging area to the last commit.
3. **`git reset --soft HEAD~1`**: Moves the HEAD pointer back by one commit, but keeps the changes staged.
4. **`git revert <commit>`**: Creates a new commit that undoes the changes made by a specific commit.
5. **`git checkout -- <file>`**: Discards changes in the working directory to the last committed state.

## Stashing Changes
1. **`git stash`**: Temporarily saves (stashes) changes in your working directory.
2. **`git stash apply`**: Re-applies the last stashed changes.
3. **`git stash list`**: Lists all stashed changes.

## Logs and History
1. **`git log`**: Shows the commit history.
2. **`git log --oneline`**: Shows the commit history in a condensed form.
3. **`git show <commit>`**: Shows details of a specific commit.

## Tagging
1. **`git tag <tag-name>`**: Creates a tag for the current commit.
2. **`git tag`**: Lists all tags.
3. **`git push origin <tag-name>`**: Pushes a tag to the remote repository.

## Collaborating
1. **`git pull origin <branch-name>`**: Fetches and merges changes from a remote branch into the current branch.
2. **`git rebase <branch>`**: Re-applies commits on top of another branch, used for cleaning up commit history.

## Others
1. **`git rm <file>`**: Removes a file from both the working directory and the staging area.
2. **`git mv <old-name> <new-name>`**: Renames a file and stages the change.
3. **`git blame <file>`**: Shows who made changes to each line of a file.
4. **`git cherry-pick <commit>`**: Applies a specific commit to your current branch.

## Basic Workflow Example
1. **Initialize Repository**:
   ```bash
   git init
   ```
2. **Add Remote**:
   ```bash
   git remote add origin <repository-url>
   ```
3. **Create Branch and Switch**:
   ```bash
   git checkout -b feature-branch
   ```
4. **Add Changes**:
   ```bash
   git add .
   ```
5. **Commit Changes**:
   ```bash
   git commit -m "Add new feature"
   ```
6. **Push Changes to Remote**:
   ```bash
   git push origin feature-branch
   ```

This summary of Git commands provides an overview of the most commonly used operations. Let me know if you need more detailed information on any particular command or workflow!
