# debug:plugin
Affiche tous les types de plugins, les instances de plugin d'un certain type, ou la définition d'un plugin spécifique.

**Usage:**
```
drupal debug:plugin [arguments]
dpl
```

## Available arguments
Argument | Details
---------|-------------
type | Type de plugin
id | ID du plugin

## Examples
* Displays a list with all the plugins on the current site
```
drupal debug:plugin
```
* Displays block plugin information
```
drupal debug:plugin block
```
* Displays block broken information
```
drupal debug:plugin block broken
```
