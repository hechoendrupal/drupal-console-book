# database:restore
Restaurar a estrutura e conteúdo das bases de dados e tabelas do MySQL

**Usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## Available options
Option | Details
-------|-------------
--file | O nome do arquivo de backup do banco de dados

## Available arguments
Argument | Details
---------|-------------
database | Senha do banco de dados em settings.php

## Examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
