# generate:plugin:migrate:process
Generate a migrate process plugin

**Ús:**
```
drupal generate:plugin:migrate:process [options]
gpmp
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--class | Plugin class name
--plugin-id | Plugin id

## Exemples
* Generate a migration plugin process specifying the module name, the class and its id
```
drupal generate:plugin:migrate:process  \
  --module="modulename"  \
  --class="MigrationProcess"  \
  --plugin-id="migrationprocess"
```
