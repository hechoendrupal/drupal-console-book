# database:log:clear
DbLogからイベントを削除する

**Usage:**
```
drupal database:log:clear [arguments] [options]
dblc
```

## Available options
Option | Details
-------|-------------
--type | イベントを特定のタイプでフィルタする
--severity | イベントを特定の重要度のレベルでフィルタする
--user-id | イベントを特定のユーザーIDでフィルタする

## Available arguments
Argument | Details
---------|-------------
event-id | DBLogのイベントID

## Examples
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
