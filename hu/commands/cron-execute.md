# cron:execute
Cron megvalósítások végrehajtása modul szerint, vagy az összes cron metódus végrehajtása

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal cron:execute [arguments]
$ croe  
$ cre  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
module | A modul neve.

## commands.generate.doc.gitbook.messages.examples
* Execute the cron globally
```
$ drupal cron:execute

```
* Execute the cron on the specified module
```
$ drupal cron:execute \
  <module>

```
