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