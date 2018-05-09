# database:add
Add a database to settings.php

**Usage:**
```
drupal database:add [options]
dba
```

## Available options
Option | Details
-------|-------------
--database | The database name
--username | The database username
--password | The database password
--prefix | The database prefix
--host | The database host address
--port | The database host port
--driver | The database driver

## Examples
* Add a database to the settings.php
```
drupal database:add \
  --database=DATABASE \
  --username=USERNAME \
  --password=PASSWORD
```
