# database:log:clear
清除事件日志

**Usage:**
```
drupal database:log:clear [arguments] [options]
dblc
```

## Available options
Option | Details
-------|-------------
--type | 用指定类型过滤事件
--severity | 用指定的严重等级过滤事件
--user-id | 用指定的用户ID过滤事件

## Available arguments
Argument | Details
---------|-------------
event-id | DBLog 事件 ID

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
