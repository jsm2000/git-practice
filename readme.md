
#practice repo to start learning Git

## command used
- git init: inits a repo
- git stats; comapres working dir, staging area and current branch
- git add: ad changes from working dir to staging area
- git commit -m "<message>": commits changes from staging to current branch
- git log: show a history (aka log) of commits
- git checkout <branch name>: check out (switch to) a branch 
- git checkout -b <new branch> : creates branch then check it out
- git branch -c <branch name>:  create branch
- git branch: list branches
- git stash: stash changes from working directory
- git stash list: list stashed changes
- git stash pop: apply stashed changes to working directory
- git merge; merge changes from different branches
- git show: show a single commit
- git diff: show the difference between commits, the working directory and the staging area

## Merging
Merging means to bring the changes from one branch into another.

- A fast-forward merge happens when the target branch was branched from the current one, and t here are no new changes to the current branch since then.
-An automatic merge happens when the two histories have diverged but git is able to reconsile then into one set of changes.  This create a new commit on the current branch.

