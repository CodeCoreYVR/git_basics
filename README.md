# git_basics

#git branching and merging practise

A branch is a series of commits

We can create a new branch using `git branch "<name_of_branch>"`
The new branch's root commit will be master commit of the branch you've "branched off of"

# fetch vs pull

git fetch -> getting all the commits from remote (github)

git merge -> merge commits from a branch into HEAD (branch)

git pull -> does a git fetch and a git merge after

# To delete local branch
git branch -D <branch name>

# To rename local branch
git branch -m <oldname> <newname>

