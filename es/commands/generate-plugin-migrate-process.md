# generate:plugin:migrate:process
Genera un plugin de proceso para migración

**Usage:**
```
drupal generate:plugin:migrate:process [options]
gpmp
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del plugin
--plugin-id | ID del Plugin

## Examples
* Generate a migration plugin process specifying the module name, the class and its id
```
drupal generate:plugin:migrate:process  \
  --module="modulename"  \
  --class="MigrationProcess"  \
  --plugin-id="migrationprocess"
```
