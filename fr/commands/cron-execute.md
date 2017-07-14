# cron:execute
Lancer une tâche cron d'un module particulier ou l'ensembles des tâches

**Usage:**
```
drupal cron:execute [arguments]
croe
cre
```

## Available arguments
Argument | Details
---------|-------------
module | Le nom du module.

## Examples
* Execute the cron globally
```
drupal cron:execute
```
* Execute the cron on the specified module
```
drupal cron:execute \
  <module>
```
