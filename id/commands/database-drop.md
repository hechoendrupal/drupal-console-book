# database:drop
Hapus semua tabel pada basis data terpilih.

**application.gitbook.messages.usage:**
```
drupal database:drop [arguments]
dbd
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Key basis data pada settings.php

## application.gitbook.messages.examples
* Drop the tables on the database specified on the argument
```
drupal database:drop \
  <database>
```
