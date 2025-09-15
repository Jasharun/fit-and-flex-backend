# metroblend-backend
Backend service for metroblend e-commerce app

# 0) Make sure you committed your code locally
git status
git add -A
git commit -m "first commit: Spring Boot backend"

# 1) Make sure your branch is called main
git branch -M main

# 2) Link/verify the remote
git remote -v
# If origin isn’t set correctly:
# git remote set-url origin https://github.com/Jasharun/metroblend-backend.git

# 3) Pull the remote commit(s) into your local branch, then push
git pull --rebase origin main --allow-unrelated-histories
# (Resolve any conflicts if prompted, then:)
git push -u origin main

