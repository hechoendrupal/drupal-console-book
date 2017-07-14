# database:connect
Lanzar un cliente de base de datos si está disponible

**application.gitbook.messages.usage:**
```
drupal database:connect [arguments]
dbco
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Clave de base de datos, desde settings.php

## application.gitbook.messages.examples
* Connects to an specified database, or the default if not arguments passed
```
drupal database:connect \
  <database>
```
