# database:restore
Restaure la structure et le contenu de votre base de données MySQL depuis une sauvegarde

**application.gitbook.messages.usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file | Le nom du fichier de votre sauvegarde de base de données

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Clé de la base de données du fichier settings.php

## application.gitbook.messages.examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
