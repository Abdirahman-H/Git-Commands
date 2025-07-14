# 🚀 Git Commands Cheat Sheet
Command	Description
git init	Initialize a new Git repository.
git clone <url>	Copy an existing remote repository.
git status	Show the current status of files (tracked/untracked/modified).
git add <file>	Stage a file for commit.
git add .	Stage all changes in the current directory.
git commit -m "message"	Save staged changes with a commit message.
git log	View commit history.
git diff	Show changes not yet staged.
git push origin <branch>	Push local commits to the remote repository.
git pull origin <branch>	Fetch and merge remote changes.
git branch	List branches.
git branch <name>	Create a new branch.
git checkout <branch>	Switch to a branch.
git checkout -b <branch>	Create and switch to a new branch.
git merge <branch>	Merge another branch into the current one.
git reset --soft HEAD~1	Undo last commit (keep changes staged).
git reset --hard HEAD~1	Remove last commit and discard changes.
git revert <commit>	Create a new commit that undoes a previous one.
git stash	Save uncommitted changes temporarily.
git stash pop	Reapply stashed changes.
git rebase <branch>	Move current branch commits on top of another.
git cherry-pick <commit>	Apply a single commit from another branch.
git rm <file>	Remove a file from repo and staging.
.gitignore	File used to tell Git which files/folders to ignore.