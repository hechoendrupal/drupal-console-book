# migrate:execute
Tiến hành một phần chuyển đổi dữ liệu có sẵn trong ứng dụng

**Usage:**
```
drupal migrate:execute [arguments] [options]
mie
```

## Available options
Option | Details
-------|-------------
--site-url | Nguồn URL
--db-type | commands.migrate.execute.migrations.options.db-type
--db-host | Máy chủ cơ sở dữ liệu
--db-name | Tên cơ sở dữ liệu
--db-user | Người dùng cơ sở dữ liệu
--db-pass | Mật khẩu cơ sở dữ liệu
--db-prefix | Tiền tố cơ sở dữ liệu
--db-port | Cổng vào cơ sở dữ liệu
--exclude | Các ID của phần chuyển đổi dữ liệu để loại trừ
--source-base_path | Local file directory containing your source site (e.g. /var/www/docroot), or your site address (for example http://example.com)

## Available arguments
Argument | Details
---------|-------------
migration-ids | Các ID của phần chuyển đổi dữ liệu
