# github

## Basic Git commands

Check out a repository

Create a working copy of a local repository:	

git clone /path/to/repository

git init

`git add <filename>`

git add *

git commit -m "Commit message"

git commit -a

git push origin master

git status

`git checkout -b <branchname>`

`git checkout <branchname>`

`git branch -d <branchname>`

`git push origin <branchname>`

git push --all origin

`git push origin :<branchname>`

git pull

git log

git push --tags origin

git fetch origin

---------git pull force-----------------

git fetch --all

git reset --hard origin/master

git reset --hard origin/<branch_name>

-----------------------------------------------
`
…or create a new repository on the command line
echo "# elearning" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/sarveshhome/elearning.git
git push -u origin master
                
…or push an existing repository from the command line
git remote add origin https://github.com/sarveshhome/elearning.git
git push -u origin master `



---------------------------------------------------

Source [link](https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html)
