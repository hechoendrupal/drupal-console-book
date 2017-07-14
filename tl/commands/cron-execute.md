# cron:execute
Jalankan implementasi cron oleh modul atau jalankan semua cron-cron

**Usage:**
```
drupal cron:execute [arguments]
croe
cre
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
