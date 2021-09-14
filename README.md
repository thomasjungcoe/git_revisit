# ============================================================
# Git Revisited
# ============================================================

# ============================================================
# Getting Started
# 1.) Setting up a repository 
# ============================================================

mkdir repo
cd repo
touch readme.txt

# initialize empty Git repo 
git init

# You can also clone an existing remote repositories using the folowing commands:
git clone <repo url>

# tell git 'readme.txt' exists in this repo
git add readme.txt

# check for the status of the system
git status

# Commit to the staged files into git repo
git commit -m "message"

# Check the history of the commits
git log

# ============================================================
# 2.) Saving changes 
# ============================================================

# map remote repo at () to a ref in local repo
git remote add <remote_name> <remote_repo_url>

# push the local repo branch to remote repo
# also had to create shh credentials for pushing
git push -u origin master





# ============================================================
# 3.) Inspecting a repository
# ============================================================





# ============================================================
# 4.) Undoing changes
# ============================================================



# ============================================================
# 5.) Rewriting history
# ============================================================




