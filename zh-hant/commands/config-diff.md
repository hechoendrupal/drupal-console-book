# config:diff
Ouput configuration items that are different in active configuration compared with a directory.

**application.gitbook.messages.usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--reverse | See the changes in reverse (i.e diff a directory to the active configuration).

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
directory | The directory to diff against. If omitted, choose from Drupal config directories.

## application.gitbook.messages.examples
* Provide a config directory
```
drupal config:diff ../config/path
```
