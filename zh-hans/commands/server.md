# server
運行內建的 PHP 網頁伺服器

**application.gitbook.messages.usage:**
```
drupal server [arguments]
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
address | 伺服器位址:連接埠（address:port）參數

## application.gitbook.messages.examples
<<<<<<< HEAD
* 用缺省地址和端口127.0.0.1:8088
```
Drupal服务器
=======
* 以預設伺服器位址（127.0.0.1:8088）啟動伺服器
```
drupal server
>>>>>>> upstream/master
```
* 以指定的伺服器位址參數啟動伺服器
```
<<<<<<< HEAD
Drupal服务器127.0.0.1:8089
=======
drupal server 127.0.0.1:8089
>>>>>>> upstream/master
```
* 以預設伺服器位址啟動伺服器，加上 --root 參數以指定 Drupal 所在路徑
```
<<<<<<< HEAD
Drupal --root=/var/www/drupal8.dev server
=======
drupal --root=/var/www/drupal8.dev server
>>>>>>> upstream/master
```
