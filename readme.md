
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
- git remote add <remote> <url>: at a new remote at URL
- git remote -v: list remote repos
- git push -u <remote> <branch>: Push branch to remote and set default upstream for branch
- git fetch: fetches changes from remote repo
- git pull: fetch and then merge


## Merging
Merging means to bring the changes from one branch into another.

- A fast-forward merge happens when the target branch was branched from the current one, and t here are no new changes to the current branch since then.
-An automatic merge happens when the two histories have diverged but git is able to reconsile then into one set of changes.  This create a new commit on the current branch.

## What's a remote repo?

A remote repo is one hosted somewhere other than our local machine.  We can add remotes with 'git remote add', and set up *tracking branches* to track differences between our local and our remote repos.

We push to remotes with 'git push', and fetch from them with 'git fetch'.  We can also fetch and merge in one set with 'git pull'.
