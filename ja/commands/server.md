# server
PHPのbuilt-in web serverでDrupalを起動する

**application.gitbook.messages.usage:**
```
drupal server [arguments]
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
address | IPアドレスとポート番号

## application.gitbook.messages.examples
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
