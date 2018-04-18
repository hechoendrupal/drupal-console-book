# debug:database:table
Show all tables in a given database.

**Utilização:**
```
drupal debug:database:table [arguments] [options]
ddt
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--database | Database key from settings.php

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
table | Table to debug

## Exemplos
* Show all tables on a database
```
drupal debug:database:table
```
* Show fields on the node table or another specified on the argument
```
drupal debug:database:table node
```
