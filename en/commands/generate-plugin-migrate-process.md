# generate:plugin:migrate:process
Generate a migrate process plugin

**application.gitbook.messages.usage:**
```
drupal generate:plugin:migrate:process [options]
gpmp
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | The Module name.
--class | Plugin class name
--plugin-id | Plugin id

## application.gitbook.messages.examples
* Generate a migration plugin process specifying the module name, the class and its id
```
drupal generate:plugin:migrate:process  \
  --module="modulename"  \
  --class="MigrationProcess"  \
  --plugin-id="migrationprocess"
```
