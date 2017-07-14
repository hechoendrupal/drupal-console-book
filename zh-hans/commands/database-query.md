# database:query
commands.database.query.description

**application.gitbook.messages.usage:**
```
drupal database:query [arguments] [options]
dbq
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--quick | commands.database.query.options.quick
--debug | commands.database.query.options.debug
--html | commands.database.query.options.html
--xml | commands.database.query.options.xml
--raw | commands.database.query.options.raw
--vertical | commands.database.query.options.vertical
--batch | commands.database.query.options.batch

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
<<<<<<< HEAD
query | The SQL statement to execute
database | Database key from settings.php

## application.gitbook.messages.examples
* Send a database query
```
drupal database:query 'select * from node limit 0,1'
```
=======
query | commands.database.query.arguments.query
database | commands.database.query.arguments.database
>>>>>>> upstream/master
