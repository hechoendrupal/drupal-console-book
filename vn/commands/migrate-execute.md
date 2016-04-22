# migrate:execute
Tiến hành một phần chuyển đổi dữ liệu có sẵn trong ứng dụng

**Usage:**
```
$ drupal migrate:execute [arguments] [options]
$ mie  
```

## Các tùy chọn có sẵn
Tùy chọn | Các chi tiết
-------|-------------
--site-url | Nguồn URL
--db-type | commands.migrate.setup.migrations.options.db-type
--db-host | Máy chủ cơ sở dữ liệu
--db-name | Tên cơ sở dữ liệu
--db-user | Người dùng cơ sở dữ liệu
--db-pass | Mật khẩu cơ sở dữ liệu
--db-prefix | Tiền tố cơ sở dữ liệu
--db-port | Cổng vào cơ sở dữ liệu
--exclude | Các ID của phần chuyển đổi dữ liệu để loại trừ

## Các đối số có sẵn
Đối số | Các chi tiết
---------|-------------
migration-ids | Các ID của phần chuyển đổi dữ liệu
