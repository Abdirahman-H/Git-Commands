# 📘 My Git Journey: Key Git Commands Explained
# 📂 What's Inside

# This repository includes:

# - ✅ Commonly used Git commands
# - 📖 Examples and syntax
# - 🛠️ Use-case explanations
# - 💡 Best practices

➕ Stage Changes
git add <file>      # Stage a specific file
git add .           # Stage all files in the directory


✅ Commit Changes
git commit -m "your message"
Save your staged changes to the history with a message.


⬆️ Push Changes
git push origin main
Push committed changes to a remote repository.


⬇️ Pull Latest Changes
git pull origin main
Fetch and merge changes from the remote branch.


🔍 Check Status
git status
See what’s modified, staged, or untracked.


📜 View History
git log


🔄 Branching
git branch                      # List branches
git branch feature-xyz         # Create new branch
git checkout feature-xyz       # Switch to branch
git checkout -b feature-abc    # Create & switch


🔀 Merge
git checkout main
git merge feature-xyz
Merge another branch into the main branch.


🧼 Stash Changes
git stash
git stash apply
Temporarily store unfinished changes.


🛠️ Revert Changes
git revert <commit-hash>


❗ Reset
git reset --soft HEAD~1    # Undo last commit (keep changes staged)
git reset --hard HEAD~1    # Delete last commit and changes
🍒 Cherry-pick


git cherry-pick <commit-hash>
Apply a specific commit from another branch.

🔄 Rebase
git rebase main
Reapply commits from one branch on top of another.


🛑 .gitignore Example
gitignore

# Ignore node_modules
node_modules/

# Ignore logs
*.log

# Ignore environment files
.env


🧠 Tip
Commit early, commit often — and write meaningful commit messages!

📬 Contributions
Feel free to fork and contribute with pull requests, or suggest updates by opening an issue.