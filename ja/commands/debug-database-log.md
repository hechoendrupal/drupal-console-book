# debug:database:log
DBLogのイベントを表示

**Usage:**
```
drupal debug:database:log [arguments] [options]
dbb
ws
```

## Available options
Option | Details
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id
--asc | イベントの一覧を昇順で表示
--limit | 結果の表示件数を指定した値に制限
--offset | オフセット
--yml | Print in a yml style

## Available arguments
Argument | Details
---------|-------------
event-id | DBLogのイベントID

## Examples
* List all the entries on the log
```
drupal debug:database:log
```
* List specific log entry by Event ID
```
drupal debug:database:log 21228
```
