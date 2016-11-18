# Git_Command_Explore
This repository is created to demonstrate git command.


Git Commands:
Git status - Give current local repo status.
Git log - gives git commit history.
git checkout master - checkout master branch.
git remote -v - shows remote version .

Synchronize:
git remote add upstream https://RAGHUKA@ctlabs.verizon.net/stash/scm/fm/fiosmobileiptv-ios-dev.git
git fetch upstream
git merge upstream/master

Clean:
git reset --hard HEAD
git clean -fd - clean force directory.


List commits by a user:
git log --since=20.days --author=karthik



Steps to revert if a local commit has conflict with remote:
git merge --abort
git reset --soft HEAD~1

Git Diff: (b/t branch of a file)
git diff 6.0 origin/release/5.3 -- AddFavoriteTask.h
