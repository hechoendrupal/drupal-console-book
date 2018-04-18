# database:drop
Drop all tables in a given database.

**Utilização:**
```
drupal database:drop [arguments]
dbd
```

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
database | Database key from settings.php

## Exemplos
* Drop the tables on the database specified on the argument
```
drupal database:drop \
  <database>
```
