# aiatuci.github.io

use command git pull https://github.com/aiatuci/aiatuci.github.io.git to get a local version on your machine.

Create the branch on your local machine and switch in this branch:
$ git checkout -b [name_of_your_new_branch]

Change working branch:
$ git checkout [name_of_your_new_branch]

Push the branch on github:
$ git push origin [name_of_your_new_branch]

You can see all branches created by using:
$ git branch

After branch is up to date with your local computer, you can safely merge your branch with master branch by doing the following:
$ git checkout master
$ git pull origin master
$ git merge test
$ git push origin master
