# Git Commands 

## Configuration

`git config`

For all projects:

```
git config –global user.name "[name]"
git config –global user.email "[email address]"
```

For a specific project:

```$ git config –local user.name "[name]"
git config –local user.email "[email address]"
```

## Initialize

`git init`

## Clone

`git clone [url]` 

**Adding files to the staging area**

 `git add .`
 `git add [file name]`

## Commit

`git commit -m "[commit message]"`

## Status

git status


## Remove

git rm [file]

A file is removed from the working directory using this command.

## Reset

`git reset [file]`

git reset [commit]

git reset –hard [commit]


## Log

git log


## Brunch


git branch - Shows all the branches of the repository


git branch [branch name] - Creates a new branch 


git branch -d [branch name] - Deletes the branch 


## Checkout

git checkout [branch name] - To switch to a specific branch 


git checkout -b [branch name] - Creates a new branch and switches there


## Merge

git merge [branch name]



## Push

git push [variable name] master

git push [variable name] [branch]

git push –all [variable name]


git push [variable name] :[branch name]


## Pull

git pull [Repository Link]

## Remote

git remote add [variable name] [Remote Server Link]

## Stash

git stash save


git stash pop


git stash list


git stash drop
