# database:log:clear
清除事件日志

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:log:clear [arguments] [options]
$ dblc  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--type | 用指定类型过滤事件
--severity | 用指定的严重等级过滤事件
--user-id | 用指定的用户ID过滤事件

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
event-id | DBLog 事件 ID

## commands.generate.doc.gitbook.messages.examples
* Clear the database log from DBLog table
```
$ drupal database:log:clear \
  <database>
```
* Clear the database log from DBLog table using filters
```
$ drupal database:log:clear \
  <database> \
  --type=TYPE \
  --severity=SEVERITY
```
