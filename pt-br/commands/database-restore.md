# database:restore
Restaurar a estrutura e conteúdo das bases de dados e tabelas do MySQL

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:restore [arguments] [options]
$ dbr  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--file | O nome do arquivo de backup do banco de dados

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
database | Senha do banco de dados em settings.php

## commands.generate.doc.gitbook.messages.examples
* Restore the database file dump to the database default or another one specified
```
$ drupal database:restore \
  --file='/srv/dump/db.sql'

```
