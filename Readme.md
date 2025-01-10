# Git Branching (Used for team based projects)

                                                  HotFix                           [HotFix Branch] 
                                               /          \  
                                              /            \
                                             /              \
---- Commit1 ---- Commit2 ---- Commit3 ---- Commit4 ---- merge ---- Merge ----    [This is Master Branch(Main branch)]
                                \                                      /
                                 \                                    /
                                  \                                  /
                                 feature1 ----- feature2 ----- feature3                [feature branch]


## Master Branch 
*  This is the main branch Where the program exists [Main branch]

## We can make a Feature Branch
*  This branch is used for adding new features to the project
*  Changes done in this branch wont show in the main branch(Master)
*  if you switch to master branch you won't see the changes
*  It's like a sandbox where you write your code make it perfect before merging with main branch

## HOTFIX
*  This branch is made and used for fixing the bugs in the projects

### To check branches 
*   Type "git branch"
*   This will show you how many branches are there

## To make a new Branch
*  Type "git checkout -b [name of the branch]" (brackets excluded)
*  ex: git checkout -b feature-readme-gitBranching
*  Switched to a new branch 'feature-readme-gitBranching' (It will look something like this)

## How to switch b/w branches
*  Type "git checkout [master/feature-readme-gitBranching]" (brackets excluded)
*  In square Brackets u need to put the name of the branch
*  Switched to branch 'master' (It will look something like this)
 
## to check the difference b/n the feature and master
*  type "git diff [name of the feature branch]"

## New Topic

   Information

* The above 2 lines are for practice purpose

## How to make a pull request and merge the feature branch to the Master/Main branch
*  Save everthing in the f-branch and commit the branch
*  After commit push the branch to the remote repository
*  ex: "git push -u origin [name of the feature branch]"
       "git push -u origin feature-readme-gitBranching"
*  Whenever you push you will get a link for pr(Pull Request)
###  You can do manually from the gitHub page 
*    After you push you will see a notification
*    That a new branch is added with a button 
*    Compare and Merge
*    if you have some issue you can resolve right there
*    Once resolved You can merge
*    additional INFO: You can also add comments in the lines which are changed/modified

### After merging in the github page
*   You will see the that the files have been merged in the code
*   you will be in the master branch
*   These changes will not show in the local device
*   Go to the terminal and go to the master branch
*   To get the changes in the local device
*   Type "git pull" - If you have upstreamed already OR
*   Type "git pull origin master"

### Deleting a branch
*   Type "git branch -d [name of the branch]"
*   ex" "git branch -d feature-readme-gitBranching"
*   You will see something like this in the terminal
*   "Deleted branch feature-readme-gitBranching (was 391b6a7)."
