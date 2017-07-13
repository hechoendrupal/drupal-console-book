# cron:execute
执行模块中的或所有的定时任务（cron）

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal cron:execute [arguments]
$ croe  
$ cre  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
module | 模块名称

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
