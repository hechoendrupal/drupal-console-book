# cron:execute
Execute cron implementations by module or execute all crons

**Usage:**
```
drupal cron:execute [arguments]
croe
```

## Available arguments
Argument | Details
---------|-------------
module | The Module name.

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
