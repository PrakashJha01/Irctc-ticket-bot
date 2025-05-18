commit in GitHub, it saves history in form of history
configure git globl username global vs locacl config
global config --global user.email " 
git config.list
root directory symbol

clone command remote local get the link from  repo
cd //change directory
clear
ls //list files
ls -a // will show hidden files as well

git status //up to date modified
add -> commit
untracked
modified
staged (add)
unmodified

Add & Commit work on working directory to git staging area
git add filename
git add .
commit is the record of change
git commit -m "meaningful msg"

msg: your branch is ahead of 'origin/main' by 1 commit meaning

Push command
upload local repo content to remote repo
git push origin main
meaning: 
	git push is the basic command to puch code,origin is the link to remote directory -> main is the branch

What is a branch

init command
mkdir localrepo
now we will make the changes in local repo

git init
then we can use the feature of git in the local repo
git add
git commit -m"add initial files"

Now we want to upload the file in a repo
then create a new repo

git remote add origin <link to repo>
git remote -v // to verify the repo
git branch (to check the branch)
what is branch here undertand the usecase with example: this will make the copy of the code from the point where the branch is originated
 example 3 team 3 branch front back and bug fix

git branch -M main
git push origin main

or git puch -u origin main set upstream// to create shortform to use git push

README.md

Workflow

local git
GitHub repo - > clone - > changes - > add -> commit -> push

Git Branches (master feature)
then merge point


Branch command
git branch
git branch -M main
git checkout other_branch_name // to switch branch
git checkout -b feature1 // to create branch
git branch -d feature2

Merge code
git diff branchname //to compare commit, branches, files and more code difference is shown
git merge

create a pr: it letsyou tell others about changes you'll push to a branch. this let senior developer review the chanes to be made in the code

issues with merge is conflict of line


Pull command
git pull origin main
used to fetch and download content from a remote repo and immediately update the content amd let us know the differences betn two commits

Resolving merge conflicts: 

