# database:dump
Exporte la structure et le contenu de votre base de données MySQL

**application.gitbook.messages.usage:**
```
drupal database:dump [arguments] [options]
dbdu
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file | Le nom du fichier pour votre sauvegarde de base de données
--gz | Pass this option if you want the sql result file gzipped

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Clé de la base de données du fichier settings.php

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
