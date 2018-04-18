# debug:database:log
Hiển thị các dấu sự kiện hiện tại cho ứng dụng

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
--asc | List events in ascending order
--limit | Giới hạn kết quả cho một số cụ thể
--offset | Điểm bắt đầu của một giới hạn
--yml | Print in a yml style

## Available arguments
Argument | Details
---------|-------------
event-id | DBlog sự kiện ID

## Examples
* List all the entries on the log
```
drupal debug:database:log
```
* List specific log entry by Event ID
```
drupal debug:database:log 21228
```
