# database:query
Executes a SQL statement directly as argument

**Utilização:**
```
drupal database:query [arguments] [options]
dbq
sqlq
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--quick | Do not cache each query result, print each row as it is received
--debug | Prints debugging information and memory and CPU usage statistics when the program exits
--html | Produce HTML output
--xml | Produce XML output
--raw | Special characters are not escaped in the output.
--vertical | Print query output rows vertically
--batch | Print results using tab as the column separator, with each row on a new line. With this option, mysql does not use the history file

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
query | The SQL statement to execute
database | Database key from settings.php

## Exemplos
* Send a database query
```
drupal database:query 'select * from node limit 0,1'
```
