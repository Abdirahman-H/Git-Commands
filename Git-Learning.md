📘 Git Commands – What They Do and Why They're Important

**git init**
Initializes a new Git repository in your current directory.
This creates the .git folder that tracks all changes to your project files.
Why it matters: It’s the first step to start version controlling your project.

**git add <file>**
Stages a specific file, marking it to be included in the next commit.
Why it matters: It lets you choose which changes to save in the commit, giving you control.

**git add .**
Stages all changes (new, modified, deleted files) in the current directory.
Why it matters: Quickly prepares all your changes for committing without specifying each file.

**git commit -m "message"**
Creates a commit with all staged changes and attaches a message describing what you changed.
Why it matters: Commits are snapshots of your project’s history, and clear messages help understand the changes later.

**git push origin main**
Uploads your local commits to the remote repository’s main branch (e.g., on GitHub).
Why it matters: It shares your work with others and backs it up remotely.

**git pull origin main**
Fetches changes from the remote main branch and merges them into your local branch.
Why it matters: Keeps your local copy up to date with others’ changes.

**git status**
Displays the current state of your working directory and staging area, showing modified, staged, or untracked files.
Why it matters: Helps you know what’s changed and what’s ready to commit.

**git log**
Shows the commit history with commit hashes, author, date, and messages.
Why it matters: Lets you review past changes and track progress or debug issues.

**git branch**
Lists all existing branches in your repository.
Why it matters: Helps you manage multiple lines of development.

**git branch <branch-name>**
Creates a new branch with the given name.
Why it matters: Allows you to work on features or fixes without affecting the main codebase.

**git checkout <branch-name>**
Switches your working directory to the specified branch.
Why it matters: Lets you move between different versions or features of your project.

**git checkout -b <branch-name>**
Creates a new branch and switches to it immediately.
Why it matters: Quickly starts new work without separate branch creation and switching steps.

**git merge <branch-name>**
Combines the specified branch into your current branch, integrating changes.
Why it matters: Brings new features or fixes into your current work.

**git reset --soft HEAD~1**
Moves the branch pointer back one commit but keeps your changes staged.
Why it matters: Lets you undo a commit while keeping your work ready for a new commit.

**git reset --hard HEAD~1**
Moves the branch pointer back one commit and discards all changes.
Why it matters: Completely removes the last commit and changes — useful for mistakes, but dangerous if used carelessly.

**git revert <commit-hash>**
Creates a new commit that undoes the changes from a specific previous commit.
Why it matters: Safely undoes a bad commit without altering the commit history.

**git stash**
Temporarily saves your uncommitted changes and cleans your working directory.
Why it matters: Lets you switch tasks or branches without losing unfinished work.

**git stash apply**
Reapplies your stashed changes but keeps them saved in the stash list.
Why it matters: Lets you test or review your saved changes multiple times.

**git stash pop**
Reapplies your stashed changes and removes them from the stash list.
Why it matters: Restores your saved work and cleans the stash list.

**git cherry-pick <commit-hash>**
Applies a specific commit from another branch onto your current branch.
Why it matters: Lets you selectively apply important fixes or features without merging entire branches.

**git rebase <branch>**
Moves your current branch’s commits on top of another branch’s commits, rewriting history to create a linear sequence.
Why it matters: Keeps history clean and easier to follow, especially before merging.

**.gitignore**
A file specifying patterns for files and directories that Git should ignore (not track).
Why it matters: Keeps unnecessary or sensitive files (like build artifacts, credentials) out of your repository.