# database:restore
Restabilește structura și conținutul bazei de date MySQL și ale tabelelor acesteia

**application.gitbook.messages.usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file | Numele fișierului pentru backup-ul bazei dvs. de date

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Cheia bazei de date din fișierul settings.php

## application.gitbook.messages.examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
