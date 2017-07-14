# config:diff
Output configuration items that are different in active configuration compared with a directory.

**commands.generate.doc.gitbook.messages.usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--reverse | See the changes in reverse (i.e diff a directory to the active configuration).

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
directory | The directory to diff against. If omitted, choose from Drupal config directories.

## commands.generate.doc.gitbook.messages.examples
* Provide a config directory
```
drupal config:diff ../config/path
```
