# Commands

## Basic routine

Connect to SSH adress

`ssh -T git@github.com`

Ask for git status

`git status`

adding to staging area

`git add <filename> <file_name>`

adding to local repository

`git commit -m "meaningful message"`

Add local to remote repository 

`git remote add origin <ssh address>`

If accidentally added wrong remote 

`git remote remove origin`


## From Remote to local and back

Sync remote to local

`git pull`

From remote to local 

`git clone`

From local to remote 

`git push -u origin main`

## Comparing and reverting commits

Comparing commits

`git diff & git show`

Check the history

`git log`

Recover to previous state

`git reset, git revert`

Rewrite the last commit message

`git commit -amend`

## Branching

Create a new branch
`git branch <branch_name>`

switch between branches
`git checkout <branch_name>`






