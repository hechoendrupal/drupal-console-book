# site:install
安装 Drupal

**使用方法:**
```
drupal site:install [arguments] [options]
si
```

## 可用选项
选项 | 详细信息
-------|-------------
--langcode | Drupal语言
--db-type | 要安装的Drupal数据库类型
--db-file | 要安装的Drupal数据库文件
--db-host | 数据库主机
--db-name | 数据库名称
--db-user | 数据库用户
--db-pass | 数据库密码
--db-prefix | 数据库前缀
--db-port | 数据库端口
--site-name | Drupal网站名
--site-mail | Drupal网站邮件
--account-name | Drupal管理员帐号名
--account-mail | Drupal管理员帐号邮件
--account-pass | Drupal管理员帐号密码
--force | Force to reinstall the site

## 可用参数
参数 | 详细信息
---------|-------------
profile | 要安装的Drupal配置档案

## 例子
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
