# config:import
Import configuration to current application.

**application.gitbook.messages.usage:**
```
drupal config:import [options]
ci
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file | Path to an archive file of configuration to import.
--directory | Path to a directory of configuration to import.
--remove-files | Remove files after synchronization.

## application.gitbook.messages.examples
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
