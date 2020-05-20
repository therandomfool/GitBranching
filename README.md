## Git Cheat Sheet

### Information Commands

* `git status` -status of current git repo
* `git config -l` -List of configuration of repo
* `git config --list` -List of configuration of repo

* `git log` -Log of commits in this repo
* `git log --oneline` -Compact log listing
* `git branch` - display branch information

### Basic Commands
* `git init` - Initialize a repo in a current working directory
* `git add .` - Stage current directory for commits
* `git commit -m "stuff"` - Committ staged data with message "stuff"
* `git commit` - Commit staged data enter messae in vi editor


### Branching Commands
* `git branch branchName` - Create branch 'branchname'
* `git checkout branchName` - go to branch `branchName`
* `git checkout -b branchName` - Create and check out `branchName`
* `git oull origin master` - pull `master` branch into current branchName
