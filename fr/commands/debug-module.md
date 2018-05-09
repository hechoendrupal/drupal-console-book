# debug:module
Affiche les modules actuellement disponibles dans l'application

**Usage:**
```
drupal debug:module [arguments] [options]
dm
```

## Available options
Option | Details
-------|-------------
--status | Statut du module [installed|uninstalled]
--type | Type de module [core|no-core]

## Available arguments
Argument | Details
---------|-------------
module | Module name

## Examples
* Affiche tous les modules actifs (ou installés)
```
drupal mod --status=installed
```
* Affiche tous les modules actifs qui ne sont pas du core (contrib + custom)
```
drupal mod --status=installed --type=no-core
```
