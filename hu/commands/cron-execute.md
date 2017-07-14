# cron:execute
Cron megvalósítások végrehajtása modul szerint, vagy az összes cron metódus végrehajtása

**application.gitbook.messages.usage:**
```
drupal cron:execute [arguments]
croe
cre
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
module | A modul neve.

## application.gitbook.messages.examples
* Execute the cron globally
```
drupal cron:execute
```
* Execute the cron on the specified module
```
drupal cron:execute \
  <module>
```
