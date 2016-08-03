# Drupal 8をダウンロード、インストールして起動する

ローカルマシン上でDrupal 8を試す最も簡単な方法は、以下の例のように `--file=~/.console/chain/quick-start.yml` オプションと一緒に `chain` コマンドを使う方法です。

```
$ drupal chain --file=~/.console/chain/quick-start.yml
```
> 備考: あなたのシステムに `~/.console/chain/quick-start.yml` をコピーするために、事前に `drupal init` を実行しておく必要があります。


`chain` コマンドは、実行したいコマンドやそのオプション、引数などを外部のYAMLファイルに記載し、そのファイルの定義を元にコマンドを順次実行することで、コマンドの実行を自動化します。

`~/.console/chain/quick-start.yml` の内容は以下になります。:
```
commands:
  - command: site:new
    arguments:
      directory: drupal8.dev
      version: 8.0.2
  - command: site:install
    options:
        langcode: en
        db-type: sqlite
        db-file: sites/default/files/.ht.sqlite
        site-name: 'Drupal 8 Quick Start'
        site-mail: admin@example.com
        account-name: admin
        account-mail: admin@example.com
        account-pass: admin
        generate-inline: true
    arguments:
        profile: standard
  - command: server
```

前述した例だと、いくつかのコマンドが実行されます。今回のケースでは、Drupalをダウンロードした後、SQliteを使ってインストールし、最後にPHPのビルドインサーバーが起動します。あとは単にブラウザを開き、127.0.0.1:8088 にアクセスするだけです。

あなたはYMLファイルをコピーもしくは上書きし、モジュールをダウンロードする `module:download`、モジュールをインストールする `module:install`、設定をインポートする `config:import`、データベースをリストアする `database:restore`、その他のDrupal Consoleで提供されているコマンドや、あなた自身のモジュールのカスタムコマンドを追加することができます。
