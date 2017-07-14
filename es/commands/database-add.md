# database:add
Añade una base de datos al settings.php

**Usage:**
```
drupal database:add [options]
dba
```

## Available options
Option | Details
-------|-------------
--database | El nombre de la base de datos
--username | El nombre de usuario de la base de datos
--password | La contraseña de la base de datos
--prefix | El prefijo de la base de datos
--host | La dirección del servidor de la base de datos
--port | El puerto del servidor de la base de datos
--driver | El driver de la base de datos

## Examples
* Add a database to the settings.php
```
drupal database:add \
  --database=DATABASE \
  --username=USERNAME \
  --password=PASSWORD
```
