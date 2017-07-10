# cron:execute
Execute cron implementations by module or execute all crons

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal cron:execute [arguments]
$ cre  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
module | The Module name.

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
