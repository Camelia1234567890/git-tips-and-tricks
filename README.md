# git-tips-tricks
How to use git like a pro



Installing Git
Available for Windows, IOS or Linux


Your first git commands:
git --version or git --v
clear 
*git config --global user.name "Camelia"
*git config --global user.email "camelia@gmail.com"
*git config user.name
*git help config


git clone repository

Create a repository
 git init - initialize your repository
 git status - see what untracked files you have
 git status -s - simplified
 git add . - add all your files you want to add to your commit
 git add filename.extension - add only the file you want to track

 .gitignore - add the file extension you want to ignore when tracking your files

 git restore - restore the previous version
 git commit -m "first commit" - commit the files you added

 git commit -a -m - added the file and commited it


Branching and merging
Create a new branch
git branch <name> a better option git checkout -b <new-branch-name> <source-branch-name>

git checkout -b <name> creates a new branch and also switches from main to the new branch
git merge <revision> merge into the current branch

Remotes
git fetch - retrieve reference from a remote
git pull 
git clone - download the repository from remote









