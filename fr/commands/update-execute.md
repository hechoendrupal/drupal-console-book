# update:execute
Exécute une fonction de mise à jour N dans un module, ou bien exécute toutes les fonctions

**Usage:**
```
drupal update:execute [arguments]
upex
updb
```

## Available arguments
Argument | Details
---------|-------------
module | Le nom du module.
update-n | commands.update.execute.options.update-n

## Examples
* Update all entities
```
drupal update:execute
```
* Execute updates for system module
```
drupal update:execute system
```
