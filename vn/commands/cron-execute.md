# cron:execute
Thi hành cron implementation từ một module chỉ định hoặc tất cả để thực thi tất cả các lệnh thi hành

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal cron:execute [arguments]
$ croe  
$ cre  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
module | Tên module.

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
