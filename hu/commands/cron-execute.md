# cron:execute
Cron megvalósítások végrehajtása modul szerint, vagy az összes cron metódus végrehajtása

**Usage:**
```
drupal cron:execute [arguments]
croe
cre
```

## Available arguments
Argument | Details
---------|-------------
module | A modul neve.

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
