# migrate:execute
Tiến hành một phần chuyển đổi dữ liệu có sẵn trong ứng dụng

**application.gitbook.messages.usage:**
```
drupal migrate:execute [arguments] [options]
mie
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
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
--source-base_path | commands.migrate.execute.options.source-base-path

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
migration-ids | Các ID của phần chuyển đổi dữ liệu
