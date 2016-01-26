# Keeping your fork up to date

After some time your forked repository and the original one (called upstream) will eventually get out of sync leaving you with an old, unsupported version.

To sync changes you make in a fork with the original repository, you should:

## Configuring a remote fork:
Specify and configure a new remote upstream repository that points to the upstream repository in Git.
```
git remote add upstream https://github.com/hechoendrupal/DrupalConsole.git
```
For detailed information please visit Github's guide [Configuring a remote fork](https://help.github.com/articles/configuring-a-remote-for-a-fork/)  

## Syncing your fork
Sync your fork to keep it up-to-date with the upstream repository.
```
git fetch upstream
git merge upstream/master
```
For detailed information please visit Github's guide [Syncing a fork](https://help.github.com/articles/syncing-a-fork/)
