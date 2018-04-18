# site:install
Drupalプロジェクトをインストールする

**Usage:**
```
drupal site:install [arguments] [options]
si
```

## Available options
Option | Details
-------|-------------
--langcode | Drupalの言語
--db-type | インストールに使用するデータベースのタイプ
--db-file | インストールに使用するデータベースのファイル
--db-host | Database Host
--db-name | Database Name
--db-user | Database User
--db-pass | Database Pass
--db-prefix | Database Prefix
--db-port | Database Port
--site-name | Drupalのサイト名
--site-mail | Drupalサイトのメールアドレス
--account-name | 管理者アカウントの名前
--account-mail | 管理者アカウントのメールアドレス
--account-pass | 管理者アカウントのパスワード
--force | Force to reinstall the site

## Available arguments
Argument | Details
---------|-------------
profile | Drupalのプロファイル

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
