# database:query
Executes a SQL statement directly as argument

**commands.generate.doc.gitbook.messages.usage:**
```
drupal database:query [arguments] [options]
dbq
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--quick | Do not cache each query result, print each row as it is received
--debug | Prints debugging information and memory and CPU usage statistics when the program exits
--html | Produce HTML output
--xml | Produce XML output
--raw | Special characters are not escaped in the output.
--vertical | Print query output rows vertically
--batch | Print results using tab as the column separator, with each row on a new line. With this option, mysql does not use the history file

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
query | The SQL statement to execute
database | Database key from settings.php

## commands.generate.doc.gitbook.messages.examples
* Send a database query
```
drupal database:query 'select * from node limit 0,1'
```
