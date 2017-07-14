# generate:plugin:migrate:process
Generate a migrate process plugin

**commands.generate.doc.gitbook.messages.usage:**
```
drupal generate:plugin:migrate:process [options]
gpmp
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--class | Plugin class name
--plugin-id | Plugin id

## commands.generate.doc.gitbook.messages.examples
* Generate a migration plugin process specifying the module name, the class and its id
```
drupal generate:plugin:migrate:process  \
  --module="modulename"  \
  --class="MigrationProcess"  \
  --plugin-id="migrationprocess"
```
