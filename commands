## Pre-requisite: You have to know your last commit message from your deleted branch.
git reflog
# Search for message in the list
# a901eda HEAD@{18}: commit: <last commit message>

# Now you have two options, either checkout revision or HEAD
git checkout a901eda 
# Or
git checkout HEAD@{18}

# Create branch
git branch recovered-branch

# You may want to push that back to remote
git push origin recovered-branch:recovered-branch
