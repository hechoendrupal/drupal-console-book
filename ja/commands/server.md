# server
PHPのbuilt-in web serverでDrupalを起動する

**Usage:**
```
drupal server [arguments]
serve
rs
```

## Available arguments
Argument | Details
---------|-------------
address | IPアドレスとポート番号

## Examples
* デフォルトの引数 "127.0.0.1:8088" で起動する
```
drupal server
```
* 異なるポートを使うためにアドレス引数を渡す
```
drupal server 127.0.0.1:8089
```
* デフォルトの引数で起動し、--root オプションでDrupalのルートディレクトリを指定する。
```
drupal --root=/var/www/drupal8.dev server
```
