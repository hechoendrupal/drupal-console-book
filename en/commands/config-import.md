# config:import
Import configuration to current application.

**commands.generate.doc.gitbook.messages.usage:**
```
drupal config:import [options]
ci
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--file | Path to an archive file of configuration to import.
--directory | Path to a directory of configuration to import.
--remove-files | Remove files after synchronization.

## commands.generate.doc.gitbook.messages.examples
* Provide a configuration file
```
drupal config:import \
  --file=/path/to/config/file
```
* Provide a configuration directory
```
drupal config:import  \
  --directory=/path/to/config/dir
```
