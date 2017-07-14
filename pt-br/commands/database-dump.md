# database:dump
Dump da estrutura e conteúdos da base de dados e tabelas MySQL

**application.gitbook.messages.usage:**
```
drupal database:dump [arguments] [options]
dbdu
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file |  O nome do arquivo de backup do banco de dados
--gz | Pass this option if you want the sql result file gzipped

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Senha da base de dados em settings.php

## application.gitbook.messages.examples
* Dump default database or the one specified on the argument
```
drupal database:dump \
  <database>
```
* Dump in gz compressed format
```
drupal database:dump \
  --gz
```
