# cron:execute
Выполнить cron реализацию для модуля иои выполнить все cron-задачи

**Usage:**
```
drupal cron:execute [arguments]
croe
cre
```

## Available arguments
Argument | Details
---------|-------------
module | Имя модуля.

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
