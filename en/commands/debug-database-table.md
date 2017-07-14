# debug:database:table
Show all tables in a given database.

**commands.generate.doc.gitbook.messages.usage:**
```
drupal debug:database:table [arguments] [options]
ddt
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--database | Database key from settings.php

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
table | Table to debug

## commands.generate.doc.gitbook.messages.examples
* Show all tables on a database
```
drupal debug:database:table
```
* Show fields on the node table or another specified on the argument
```
drupal debug:database:table node
```
