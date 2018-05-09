# database:add
Add a database to settings.php

**Ús:**
```
drupal database:add [options]
dba
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--database | The database name
--username | The database username
--password | The database password
--prefix | The database prefix
--host | The database host address
--port | The database host port
--driver | The database driver

## Exemples
* Add a database to the settings.php
```
drupal database:add \
  --database=DATABASE \
  --username=USERNAME \
  --password=PASSWORD
```
