# database:dump
Adatbázis szerkezetének és tartalmának kiíratása

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:dump [arguments] [options]
$ dbdu  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--file | Az adatbázis biztonsági mentésének fájlneve
--gz | Pass this option if you want the sql result file gzipped

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
database | Adatbáziskulcs a settings.php fájlból

## commands.generate.doc.gitbook.messages.examples
* Dump default database or the one specified on the argument
```
$ drupal database:dump \
  <database>
```
* Dump in gz compressed format
```
$ drupal database:dump \
  --gz
```
