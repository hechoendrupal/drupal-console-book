# update:execute
Executar una funció Update N en un mòdul, o executar-les totes

**Ús:**
```
drupal update:execute [arguments]
upex
updb
```

## Arguments disponibles
Argument | Detalls
---------|-------------
module | Nom del mòdul.
update-n | commands.update.execute.options.update-n

## Exemples
* Update all entities
```
drupal update:execute
```
* Execute updates for system module
```
drupal update:execute system
```
