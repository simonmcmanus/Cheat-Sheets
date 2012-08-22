## Git Add ##

git add .
git status


## Create New Branch FROM AN EXISTING ONE  ##



`

git stash #hide existing change
git checkout -b fullscreen
git push origin BRANCHNAME ## push branch to removgit comme git repo.


## Change Branch ## 
git checkout BRANCHNAME



## Delete Branch ##

git branch -d the_local_branch

git push origin :the_remote_branch


Making sure changes on master appear in your branch

git rebase master


git reset --hard  ## reset to ny last commit.

## Merge branch FIXED back with master ## 

git checkout master
git pull 
git submodule update --init
git checkout FIXED 
git pull 
git merge master
git submodule update --init
git push 