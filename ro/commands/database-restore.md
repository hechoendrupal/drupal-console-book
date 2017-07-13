# database:restore
Restabilește structura și conținutul bazei de date MySQL și ale tabelelor acesteia

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:restore [arguments] [options]
$ dbr  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--file | Numele fișierului pentru backup-ul bazei dvs. de date

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
database | Cheia bazei de date din fișierul settings.php

## commands.generate.doc.gitbook.messages.examples
* Restore the database file dump to the database default or another one specified
```
$ drupal database:restore \
  --file='/srv/dump/db.sql'

```
