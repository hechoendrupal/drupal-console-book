# cron:execute
Выполнить cron реализацию для модуля иои выполнить все cron-задачи

**application.gitbook.messages.usage:**
```
drupal cron:execute [arguments]
croe
cre
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
module | Имя модуля.

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
