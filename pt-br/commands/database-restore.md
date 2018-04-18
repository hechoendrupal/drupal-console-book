# database:restore
Restaurar a estrutura e conteúdo das bases de dados e tabelas do MySQL

**Utilização:**
```
drupal database:restore [arguments] [options]
dbr
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--file | O nome do arquivo de backup do banco de dados

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
database | Senha do banco de dados em settings.php

## Exemplos
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
