# server
PHPのbuilt-in web serverでDrupalを起動する

**使い方:**
```
$ drupal server [arguments]
```

## 利用可能な引数
引数 | 詳細
---------|-------------
address | IPアドレスとポート番号

## 例
* デフォルトの引数 "127.0.0.1:8088" で起動する
```
$ drupal server
```
* 異なるポートを使うためにアドレス引数を渡す
```
$ drupal server 127.0.0.1:8089
```
* デフォルトの引数で起動し、--root オプションでDrupalのルートディレクトリを指定する。
```
$ drupal --root=/var/www/drupal8.dev server
```
