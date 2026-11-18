# How to commit your messages properly

You should ensure that each commit message answers this sepecific question.

What will happen to code base when this commit is added.

Basically answering "This commit will _____________ "

when pusing to git hub use a alias "origin" this referst to the link

# **Important Commands to know of GIT**

### Create a branch

git switch -c branch-name (creating and switching)

git checkout -b branch-name ("" / older version)

git branch branch-name (Create a branch from the current branch and staying)

git switch -c branch-name another-branch (creating a branch from another branch)

git switch -c branch-name commit-hash (creating a branch from a commit)

git switch -c branch-name origin/github-branch-name (allows a different local branch name)

git switch --track origin/feature-name (this does the same as the above but does not let you to customize the local branch as you want)


### Setting up a new git and adding to github

git init

git remote add origin https://github.com/username/github_repo

(This to consider -> here the alias origin you can put any name {link, l})

### Setting up already existing local repo with a another github repo

git remote set-url origin https://github.com/username/new-repo

git push -u origin branch-name

### Renaming a branch

git branch -m new-name (this is if the current branch you need to name)

git branch -m old-name new-name

**To rename a branch that you already pushed**

git push origin -u new-name

git push origin --delete old-name

### Pushing a branch to github

**Normal push**

git push -u origin branch-name (if you want to push a code from a specific branch)

git push (this is pushing from current branch)
