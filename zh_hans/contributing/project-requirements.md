# 最低要求

## 下载 Git
推荐从[http://git-scm.com/downloads](http://git-scm.com/downloads) 下载

## 下载 Composer

获取最新版本的 Composer
```
curl -sS https://getcomposer.org/installer | php
```
如果没有 curl:
```
php -r "readfile('https://getcomposer.org/installer');" | php
```
This installer script will simply check some php.ini settings, warn you if they are set incorrectly, and then download the latest composer.phar in the current directory

You can run this terminal command to make Composer easily accessible, from anywhere on your system:
```
$ mv composer.phar /usr/local/bin/composer
```

## 下载 Drupal 8
Drupal Console 只支持 Drupal 8。需要你自己下载和安装。

### 下载 Drupal
```
$ drupal site:new drupal8.dev 8.0.0
$ cd drupal8.dev
```
### 使用 MySQL 安装 Drupal：
```
$ drupal site:install standard --langcode=en --db-type=mysql --db-host=127.0.0.1 
  --db-name=drupal --db-user=root --db-pass=root --db-port=3306 
  --site-name="Drupal 8 Site Install" --site-mail=admin@example.com 
  --account-name=admin --account-mail=admin@example.com --account-pass=admin -n
```
### 使用 SQLite 安装 Drupal
```
$ drupal site:install standard --langcode=en --db-type=sqlite 
  --db-file=sites/default/files/.ht.sqlite --site-name="Drupal 8 Site Install" 
  --site-mail=admin@example.com --account-name=admin --account-mail=admin@example.com
  --account-pass=admin -n
```
### 启动 PHP 内建服务器
```
$ drupal server
```
**注意：** Make sure you use your own user and database credentials when running `site:install` and never user root on production. In this example code, we accept all interactive questions, i.e. answering *“yes”* when passing the `-y` argument.
