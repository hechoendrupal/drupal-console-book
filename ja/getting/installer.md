# Drupal Consoleインストーラーを使う

インストーラーをローカルマシン上で実行することで、Drupal Consoleをインストールすることができます。インストーラーはDrupal Consoleを動かすために必要なファイルをダウンロードします。

## curlを使う場合:
```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
```
## curlを持っていない場合:
```
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar
```

## Drupal Consoleを実行する:
```
$ php drupal.phar
```

あなたはこのファイルをどこにでも配置することができます。パスが通っているディレクトリに配置すれば、グローバルにアクセスすることが可能です。UNIX系のシステムではphpなしで実行することもできます。

### システム上のどこからでもアクセスできるようにする
```
$ mv drupal.phar /usr/local/bin/drupal
```

### ダウンロードしたファイルに実行権限を付与する:
```
$ chmod +x /usr/local/bin/drupal
```

#### Drupal Consoleを実行する:
```
$ drupal
```

**備考:** `drupal` という名前は単なるエイリアスなので、別の名前にすることもできます。
