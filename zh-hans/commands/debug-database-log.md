# debug:database:log
显示网站日志事件(s)

**Usage:**
```
drupal debug:database:log [arguments] [options]
dbb
```

## Available options
Option | Details
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id
--asc | 按升序列出事件
--limit | 限制显示结果的数量
--offset | 偏移量
--yml | Print in a yml style

## Available arguments
Argument | Details
---------|-------------
event-id | DBLog 事件 ID

## Examples
* List all the entries on the log
```
drupal debug:database:log
```
* List specific log entry by Event ID
```
drupal debug:database:log 21228
```
