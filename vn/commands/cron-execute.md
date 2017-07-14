# cron:execute
Thi hành cron implementation từ một module chỉ định hoặc tất cả để thực thi tất cả các lệnh thi hành

**Usage:**
```
drupal cron:execute [arguments]
croe
cre
```

## Available arguments
Argument | Details
---------|-------------
module | Tên module.

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
