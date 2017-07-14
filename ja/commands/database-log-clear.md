# database:log:clear
DbLogからイベントを削除する

**application.gitbook.messages.usage:**
```
drupal database:log:clear [arguments] [options]
dblc
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--type | イベントを特定のタイプでフィルタする
--severity | イベントを特定の重要度のレベルでフィルタする
--user-id | イベントを特定のユーザーIDでフィルタする

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
event-id | DBLogのイベントID

## application.gitbook.messages.examples
* Clear the database log from DBLog table
```
drupal database:log:clear \
  <database>
```
* Clear the database log from DBLog table using filters
```
drupal database:log:clear \
  <database> \
  --type=TYPE \
  --severity=SEVERITY
```
