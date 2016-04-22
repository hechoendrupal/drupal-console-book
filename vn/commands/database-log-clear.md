# database:log:clear
Xóa các sự kiện từ DBLog table, filters là có thể sử dụng được

**Usage:**
```
$ drupal database:log:clear [arguments] [options]
```

## Các tùy chọn có sẵn
Tùy chọn | Các chi tiết
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id

## Các đối số có sẵn
Đối số | Các chi tiết
---------|-------------
event-id | DBLog event ID
