# git-tests
The purpose of this repo is to mess around with the Git CLI.

<br>

# Some helpful/useful Git CLI commands:
**Commit to GitHub (assuming there's a remote repo set up):**
git add . && git commit -m "update" && git push

**Add remote repo:**
git remote add origin https://github.com/username/repo

**View all commits:**
git log 

**View all commits, with one commit per line:**
git log --oneline

**View commit after doing git log --oneline:**
git show cb43c21


**Overwrite local repo with the remote repo:**
git fetch origin && git reset --hard origin/main && git clean -fd 

**Pull commits from remote repo (may need to overwrite the local repo):**
git pull

**Full command to add remote origin and commit:**
git remote add origin https://github.com/username/repo.git && git add . && git commit -m "Your commit message here" && git push -u origin main

