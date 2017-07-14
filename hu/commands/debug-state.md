# debug:state
Az aktuális állapotkulcsok megjelenítése.

**Usage:**
```
drupal debug:state [arguments]
dst
```

## Available arguments
Argument | Details
---------|-------------
key | Az állapotkulcs, amelyen hibakeresést kell végezni.

## Examples
* List of the states on the site
```
drupal debug:state
```
* Displays a detail of the state install_task tok from the list of states
```
drupal debug:state install_task
```
