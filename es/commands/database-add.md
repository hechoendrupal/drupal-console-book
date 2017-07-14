# database:add
Añade una base de datos al settings.php

**application.gitbook.messages.usage:**
```
drupal database:add [options]
dba
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--database | El nombre de la base de datos
--username | El nombre de usuario de la base de datos
--password | La contraseña de la base de datos
--prefix | El prefijo de la base de datos
--host | La dirección del servidor de la base de datos
--port | El puerto del servidor de la base de datos
--driver | El driver de la base de datos

## application.gitbook.messages.examples
* Add a database to the settings.php
```
drupal database:add \
  --database=DATABASE \
  --username=USERNAME \
  --password=PASSWORD
```
