## Git-Task

## VERSION CONTROL
Version Control is a system that records changes to file or set of files over time.
Version control helps us to keep track on specific changes(versions) made within these files. As a web designer Version Control System allows you to revert selected files back to previous state and see modifications made overtime.

When coolaborating with other Developers using the Centralized Version Control System(CVCS). These systems have a single server that contains all the versioned files and a number of developers that "check in" and "checkout" of files so you know which files someoneelse is working on. For many years this has been the standard for version control.


## DIFFERENCE BETWEEN GIT AND GITHUB
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and effciency . Git helps you keep track on code and to collaborate on code .

Git manages projects with repositories , clone a project to work on a local copy , control and track changes with stading and commting, allow branch and merge and more...

GitHub is a web-based Git Repository hosting service, which offers all of the distributed Revision Control and source code management functionality of Git as well as adding it's owm features 
GitHub hosts Git repositories and provides developers with tools to ship better code through command line features, issues, pull request, code review.

## GITHUB ALTERNATIVES 

- Mercurial
- Bittbucket
- Google Cloud Source Repositories

## DIFFERENCE BETWEEN GIT FETCH AND GIT PULL
Git fetch is a command used to download contents from a remote repository. When we use the git fetch, the command we fetch, commits of a remote repository into our local repository without integrating changes or altering our local work. 

The Git Pull command is used to fetch and download content from a remote repository to match the content .
Git Pull will fetch the remote version of your branch. As with more general git fetch command, this downloads the changes
from the remote branch. 
It goes a step further than git fetch by attempting to merge the remote version of the branch with your current local version.

The key difference between git fetch and pull is that git pull copies changes from a remote repository directly into your working directory , while the git fetch commands only copies changes into your local git repository.

## GIT REBASE

**git rebase main**

Rebasing is the process of moving or combining a sequence of commits to a new base commit.
What Rebase does is to take all of the commits on your feature branch and move them on top of the master commits. Behind the scenes, git is actually blowing away the feature branch commits and duplicating them as new commits on top of the master branch. Rebase is useful in incoporating changes from one branch into another.

Rebase gives you a linear project history, making it easier to understand the sequence of changes that has been made overtime.

**The Golden Rule of git rebase is to never use it on public branches**

## GIT CHERRY-PICK

**git cherry-pick <commit-hash>**

 Git Cherry-Pick(Selective Code Transfer) is a tool that allows you to select a commit from anywhere in your repository and append it to the HEAD. It's like choosing the juiciest cherry from a tree.

 It's uses varies from team collaboration in cases of shared code between two product sectors between frontend and backend developer to Bug fixies and undoing changes and restoring last commits , this is because the command creates duplicate commits. 






