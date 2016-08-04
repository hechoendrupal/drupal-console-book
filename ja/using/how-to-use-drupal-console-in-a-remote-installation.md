# Drupal Consoleでリモートサイトに接続する

Drupal Consoleはローカルサーバー上だけでなく、リモートサーバーに対してもコマンドを実行できます。

この機能を利用するためには、接続したいリモートサイトの名前を `--target` オプションを指定します。

```
$ drupal --target=sample.dev cr all
```

ローカルマシンからリモートサイトへ接続するためには、少しだけ設定が必要です。

### グローバル設定の編集

`~/.console/config.yml` でリモート接続するためのグローバル設定を提供できます。この情報は `remote` キーでグルーピングされています。
```
application:
  ...
  remote:
    user: root
    port: 22
    console: /usr/local/bin/drupal
    options:
    arguments:
    keys:
      public: ~/.ssh/id_rsa.pub
      private: ~/.ssh/id_rsa
      passphrase: ~/.ssh/passphrase.txt
```

### 特定のサイト向けの設定
`~/.console/sites/sample.yml` を複製して `~/.console/sites/` にコピーすることで、特定のサイト向けの設定を提供する事ができます。

```
local:
  root: /var/www/drupal8.dev
  host: local
dev:
  root: /var/www/html/drupal
  host: 140.211.10.62
  user: drupal
prod:
  root: /var/www/html/docroot
  host: live.drupal.org
  user: drupal
  console: /var/www/html/docroot/console.phar
```

### サイトのデバッグ
`site:debug` コマンドで、全てのローカル及びリモート上のサイトを取得することができます。
```
$ drupal site:debug

+--------------------+-----------------+------------------------+
| Site               | Host            | Root                   |
+--------------------+-----------------+------------------------+
| sample.local       | local           | /var/www/drupal8.dev   |
| sample.dev         | 140.211.10.62   | /var/www/html/drupal   |
| sample.prod        | live.drupal.org | /var/www/html/docroot  |
+--------------------+-----------------+------------------------+
```

`site:debug` コマンドの引数にサイト名を渡すと、サイトの詳細情報が表示されます。
```
$ drupal site:debug sample.dev

user: drupal
port: 22
console: /usr/local/bin/drupal
options:
arguments:
keys:
    public: ~/.ssh/id_rsa.pub
    private: ~/.ssh/id_rsa
    passphrase: ~/.ssh/passphrase.txt
root: /var/www/html/drupal
host: 140.211.10.62
remote: true
```

**備考:** サイトをデバッグするときに、グローバル設定と特定のサイト向けの設定がマージされていることに気づいたかもしれません。これらのキーを特定のサイト向けの設定に追加することで、全てのグローバル設定は上書きすることができます。
