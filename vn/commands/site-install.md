# site:install
Cài đặt một dự án Drupal

**Usage:**
```
drupal site:install [arguments] [options]
si
```

## Available options
Option | Details
-------|-------------
--langcode | Ngôn ngữDrupal
--db-type | Loại Drupal Database sẽ được sử dụng trong quá trình cài đặt
--db-file | Drupal Database file sẽ được sử dụng trong quá trình cài đặt
--db-host | Máy chủ cơ sở dữ liệu
--db-name | Tên cơ sở dữ liệu
--db-user | Người dùng cơ sở dữ liệu
--db-pass | Mật khẩu cơ sở dữ liệu
--db-prefix | Tiền tố cơ sở dữ liệu
--db-port | Cổng vào cơ sở dữ liệu
--site-name | Tên Drupal site
--site-mail | Drupal site mail
--account-name | Tên tài khoản quản trị Drupal
--account-mail | Mail tài khoản quản trị Drupal
--account-pass | Mật khẩu tài khoản quản trị Drupal
--force | Force to reinstall the site

## Available arguments
Argument | Details
---------|-------------
profile | Drupal Profile sẽ được cài đặt

## Examples
* Install a drupal project specifying installation type, language code, database configuration, site name, site email and admin credential settings
```
drupal site:install  standard  \
  --langcode="en"  \
  --db-type="mysql"  \
  --db-host="127.0.0.1"  \
  --db-name="drupal8"  \
  --db-user="u53rn4m3"  \
  --db-pass="dbp455"  \
  --db-port="3306"  \
  --site-name="Drupal 8"  \
  --site-mail="admin@example.com"  \
  --account-name="admin"  \
  --account-mail="admin@example.com"  \
  --account-pass="p455w0rd"
```
