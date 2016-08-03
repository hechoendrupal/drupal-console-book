# Drupal Consoleをマルチサイト環境で使う

Drupal Consoleはマルチサイト環境をサポートします。`multisite:debug` コマンドでマルチサイトのデバッグを行うことができ、`--uri` オプションを使うと特定のサイトと対話することができます。

### マルチサイトの一覧を表示する方法
```
$ drupal multisite:debug

+---------------------+--------------------------------+
| Site                | Directory                      |
+---------------------+--------------------------------+
| drupal8.dev         | /var/www/drupal8.dev/default   |
| drupal8.multi.dev   | /var/www/drupal8.dev/multi.dev |
+---------------------+--------------------------------+

 サイトの情報は次のフォーマットで表示されます: <port>.<domain>.<path>
```

### 特定のサイトに対してコマンドを実行する方法
```
$ drupal --uri=http://drupal8.multi.dev cr all
$ drupal --uri=drupal8.multi.dev cr all
```
