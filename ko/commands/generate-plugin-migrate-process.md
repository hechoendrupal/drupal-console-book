# generate:plugin:migrate:process
Generate a migrate process plugin

**Usage:**
```
drupal generate:plugin:migrate:process [options]
gpmp
```

## Available options
Option | Details
-------|-------------
--module | The Module name.
--class | Plugin class name
--plugin-id | Plugin id

## Examples
* Generate a migration plugin process specifying the module name, the class and its id
```
drupal generate:plugin:migrate:process  \
  --module="modulename"  \
  --class="MigrationProcess"  \
  --plugin-id="migrationprocess"
```
