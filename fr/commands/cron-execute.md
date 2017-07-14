# cron:execute
Lancer une tâche cron d'un module particulier ou l'ensembles des tâches

**application.gitbook.messages.usage:**
```
drupal cron:execute [arguments]
croe
cre
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
module | Le nom du module.

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
