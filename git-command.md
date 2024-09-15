git user and email setup

git config --global user.name
git config --global user.email

git user name and email check
git config --list

//git file create
touch readme.md

// git status check
git status

// first need to git repository init
git init

//git track . git file add
git add --all or git add readme.md or git add .

// git commit
git commit -m "Readable comment "

//commit history
git log or git log --oneline or git reflog

// git reset
git reset --hard id

// git file remove
git rm help.md
git status
git commit -m "remove help file don't need "

//git branch create
git branch dev/heading-text
git switch dev/heading-text

// branch check
git branch --list

// branch merge . you need to switch main branch
git switch main
git merge dev/heading-text
git reflog

// branch delete. you must be commit your branch
git branch -d dev/heading-text

// branch modify or rename. your must shoud stay same branch
git branch -m feature/add-heading-text
git --list

// git conflict
<<<
this text your branch
====
this text or content comming another branch

> > > git add .
> > > git commit -m "git merge"

// git stash when don't need to commit code
git stash
git stash list
git stash show -p
git stash pop or git stash apply idNumber

// git .ignore file
git rm --cached abcd.md
