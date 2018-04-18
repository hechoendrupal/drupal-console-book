# cron:execute
Executar l'implementació de cron per mòdul o executar-los tots

**Usage:**
```
drupal cron:execute [arguments]
croe
cre
```

## Available arguments
Argument | Details
---------|-------------
module | Nom del mòdul.

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
