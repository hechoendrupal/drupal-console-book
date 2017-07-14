# config:override
Az aktív konfiguráció értékének felülbírálása.

**application.gitbook.messages.usage:**
```
drupal config:override [arguments]
co
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
name | Configuration name
key | Kulcs
value | Érték

## application.gitbook.messages.examples
* A Contact modul elárasztási korlátjának beállítása 10 értékre.
```
drupal config:override contact.settings flood.limit 10
```
