# database:add
Add a database to settings.php

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:add [options]
$ dba
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--database | The database name
--username | The database username
--password | The database password
--prefix | The database prefix
--host | The database host address
--port | The database host port
--driver | The database driver

## commands.generate.doc.gitbook.messages.examples
* Add a database to the settings.php
```
drupal database:add \
  --database=DATABASE \
  --username=USERNAME \
  --password=PASSWORD
```
