# config:override
Az aktív konfiguráció értékének felülbírálása.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:override [arguments]
$ co  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
name | Configuration name
key | Kulcs
value | Érték

## commands.generate.doc.gitbook.messages.examples
* A Contact modul elárasztási korlátjának beállítása 10 értékre.
```
$ drupal config:override contact.settings flood.limit 10
```
