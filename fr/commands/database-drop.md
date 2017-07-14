# database:drop
Supprime toutes les tables d'une base de données.

**application.gitbook.messages.usage:**
```
drupal database:drop [arguments]
dbd
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Clé de la base de données du fichier settings.php

## application.gitbook.messages.examples
* Drop the tables on the database specified on the argument
```
drupal database:drop \
  <database>
```
