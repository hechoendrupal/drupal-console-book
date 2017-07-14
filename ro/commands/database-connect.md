# database:connect
Lansează un client DB dacă acesta este disponibil

**application.gitbook.messages.usage:**
```
drupal database:connect [arguments]
dbco
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Cheia bazei de date din fișierul settings.php

## application.gitbook.messages.examples
* Connects to an specified database, or the default if not arguments passed
```
drupal database:connect \
  <database>
```
