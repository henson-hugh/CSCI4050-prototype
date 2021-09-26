# CSCI4050-prototype

# Git commands
# You can always just google if you are unsure how to use a command.
git clone (https url)	clone a project from git, this means that it will be tracked by git instead of download a zip file and opening from a download
git pull 	to pull changes from the remote branch (github repository)
git fetch 	to track changes from other remote branches 
Here is an explanation for pull vs fetch https://stackoverflow.com/questions/292357/what-is-the-difference-between-git-pull-and-git-fetch 
git status	to check what files you have changed
git add .	to track the files by git in this current stage for the next commit
git add (filename…) 	to stage a specific file
git commit -m “MESSAGE”		to stage all files you tracked
git push		to push your local changes committed to the remote branch
git reset --hard 	to reset your local branch to the repository branch (this is when you have changes you don’t want to keep for reasons like someone already implemented what you worked on or you messed stuff up)
git checkout (branchname)		to checkout to another branch 
git checkout -b (branchname) 	create another branch and checkout to it
git checkout - 		checkout to the last branch you were previously on 
git diff 	to see differences from the last commit that you pulled from the remote branch