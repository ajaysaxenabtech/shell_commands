
```bash

git checkout -b feature-branch main 
git cherry-pick <commit_hash>
git push -u origin feature-branch  #-u = --set-upstream. It tells Git to link the local branch (feature-branch) with the remote branch (origin/feature-branch).



git clone <repo_url>              # Clone remote repo (GitHub) locally

git log --oneline                 # Find the commit hash(es)
git cherry-pick <commit_hash>     # Then cherry-pick one or more 
git cherry-pick <start_commit_hash>^..<end_commit_hash> # multiple commits


cd <repo_name>                    # Enter the repo directory
git status                        # See modified files
git add <file>                    # Stage specific file
git add .                         # Stage all changes
git commit -m "Your message"      # Commit staged changes
git branch                        # List local branches
git branch <branch_name>          # Create new branch
git checkout <branch_name>        # Switch to branch
git checkout -b <branch_name>     # Create and switch to new branch
git merge <branch_name>           # Merge another branch into current
git branch -d <branch_name>       # Delete local branch
git remote -v                     # Show remote URL
git remote add origin <url>       # Add GitHub remote
git push -u origin main           # Push first commit to GitHub
git push                          # Push latest commits
git pull                          # Fetch and merge changes from GitHub
git fetch                         # Only fetch, don’t merge
git log                           # View commit history
git log --oneline --graph         # Simplified commit tree
git diff                          # Show unstaged changes
git diff --staged                # Show staged changes
git restore <file>                # Undo changes in working directory
git reset <file>                  # Unstage file
git reset --hard HEAD             # Discard all local changes
