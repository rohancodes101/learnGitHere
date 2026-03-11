---

### Setup & Repo Connection

```bash
# Check Git version
git --version

# Configure user info
git config --global user.name "Your Name"
git config --global user.email "email@example.com"

# Generate SSH key for GitHub
ssh-keygen -t ed25519 -C "email@example.com"

# Clone repo in VSCode or local
git clone git@github.com:username/repo.git




git status                # Check repo status, modified/staged files
git add <file>            # Stage changes
git commit -m "msg"       # Commit staged changes
git push                  # Push commits to remote
git pull                  # Fetch and merge remote changes
git fetch                 # Fetch remote changes without merging
git log                   # View commit history
git log --oneline --graph --all  # Visual log with branches
git diff                  # Show code differences
git restore <file>        # Undo uncommitted changes
git reset <file>          # Unstage changes




git status                # Check repo status, modified/staged files
git add <file>            # Stage changes
git commit -m "msg"       # Commit staged changes
git push                  # Push commits to remote
git pull                  # Fetch and merge remote changes
git fetch                 # Fetch remote changes without merging
git log                   # View commit history
git log --oneline --graph --all  # Visual log with branches
git diff                  # Show code differences
git restore <file>        # Undo uncommitted changes
git reset <file>          # Unstage changes

git branch                # List branches
git branch <branch>       # Create new branch
git switch <branch>       # Switch branch (modern)
git checkout -b <branch>  # Switch and create branch (legacy)
git merge <branch>        # Merge a branch into current
git rebase <branch>       # Replay commits on top of another branch
git branch -d <branch>    # Safe delete branch
git branch -D <branch>    # Force delete branch


git remote -v             # Show remote repo URL
git push -u origin <branch> # Push branch and set upstream
git pull                  # Fetch + merge remote
git fetch                 # Fetch remote changes only
git log origin/<branch>   # See commits on remote

# PR Workflow
# 1. Create feature branch → commit → push
# 2. Open Pull Request on GitHub
# 3. Review → Merge → Delete branch



