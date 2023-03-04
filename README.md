# GETTING STARTED WITH GIT

## To initialized a Git repo
git init

## To check the repo status
git status

## add files to be staged i.e prepare for commit
git add <file/files/.>

## undo files from stage back to working directory
git rm --cached <file/files/.>

## publish changes/save changesto git repo
git commit -m 'your msg here'

## check git commit history
git log
git shortlog

## to create a branch and switch to the branch
git checkout -b <branchname>

## switch to a branch
git checkout <branchname>

## merge branches changes
From current branch:

git merge <other-branch>

e.g From main
git merge development

this merge changes in development to main branch

## to add a remote repository to your local copy

git remote add <name> <url>

e.g git remote add origin https://ahmed.github.com/wahab.git

## check to see if your local copy has a remote reposiorty

git remote -v

## to push to the remote server

git push <remote-name> <remote-branch>

e.g git push origin main
