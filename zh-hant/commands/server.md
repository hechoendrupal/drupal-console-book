# server
運行內建的 PHP 網頁伺服器

**Usage:**
```
drupal server [arguments]
```

## Available arguments
Argument | Details
---------|-------------
address | 伺服器位址:連接埠（address:port）參數

## Examples
* 以預設伺服器位址（127.0.0.1:8088）啟動伺服器
```
drupal server
```
* 以指定的伺服器位址參數啟動伺服器
```
drupal server 127.0.0.1:8089
```
* 以預設伺服器位址啟動伺服器，加上 --root 參數以指定 Drupal 所在路徑
```
drupal --root=/var/www/drupal8.dev server
```
