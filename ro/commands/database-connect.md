# database:connect
Lansează un client DB dacă acesta este disponibil

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:connect [arguments]
$ dbco  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
database | Cheia bazei de date din fișierul settings.php

## commands.generate.doc.gitbook.messages.examples
* Connects to an specified database, or the default if not arguments passed
```
$ drupal database:connect \
  <database>

```
