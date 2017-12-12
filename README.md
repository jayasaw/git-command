#GIT Commands


## clone repo from git 

`git clone url foldername`

## Check git working branch

`git branch`

## create new branch locally

`git branch BranchName`

## swicth to other branchs

`git checkout BranchName`

## Push all the changes of new branch created locally 

`git push --set-upstream origin BranchName`

## Otherwise use 

`git push`


## Check the status of working branch 

`git status`


## merge code from one branch to other branch

`git pull origin BranchName`


## adding new folder to the new repo url

`git init`
`git commit -m "first commit"`
`git remote add origin URL`
`git push -u -f origin master`