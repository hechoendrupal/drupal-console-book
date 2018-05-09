# debug:state
Affiche les clés de l'Etat actuel.

**Usage:**
```
drupal debug:state [arguments]
dst
```

## Available arguments
Argument | Details
---------|-------------
key | La clé de l'Etat à débugger.

## Examples
* List of the states on the site
```
drupal debug:state
```
* Displays a detail of the state install_task tok from the list of states
```
drupal debug:state install_task
```
