# debug:database:table
Show all tables in a given database.

**application.gitbook.messages.usage:**
```
drupal debug:database:table [arguments] [options]
ddt
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--database | Database key from settings.php

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
table | Table to debug

## application.gitbook.messages.examples
* Show all tables on a database
```
drupal debug:database:table
```
* Show fields on the node table or another specified on the argument
```
drupal debug:database:table node
```
