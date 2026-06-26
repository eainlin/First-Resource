## Git Command Flow
git init
git add .
git commit -m "comment"
git status
git push origin main 


## Git branch 
git branch -v
git branch test
git checkout test or git switch test
git branch -r

## Git Diff
git diff main test
git diff commit-id commit-id
git diff --stage

## Git Pull
git fetch origin
git diff main origin/main
git pull

## Git remote
git remote -v 
git remote add origin https://github.com

### Github.dev vs Codespaces
Codespaces 
- A cloud-based development environment powered by VS Code.
- Provieds fully-configurable Linux-based virtual machines with pre-installed tools.
- Supports running, debugging, and testing code in the cloud.

### Git Stash
git stash 
git stash push -m "WIP: fixing bug in API"
git stash list
git stash apply
git stash pop
git  stash apply stash@{2}

