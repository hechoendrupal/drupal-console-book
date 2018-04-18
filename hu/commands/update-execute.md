# update:execute
Egy modul adott Update N függvényének végrehajtása, vagy az összes végrehajtása

**Usage:**
```
drupal update:execute [arguments]
upex
updb
```

## Available arguments
Argument | Details
---------|-------------
module | A modul neve.
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
