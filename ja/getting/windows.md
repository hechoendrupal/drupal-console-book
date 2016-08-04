# Drupal ConsoleをWindows上にインストール
Drupal ConsoleをWindows上にインストールする方法は2つあります。Git Bashを使う方法とコマンドプロンプトを使う方法です。私達はGit for Windows (以前は msysgit と呼ばれていました)に含まれる Git Bashを使うことを推奨します。これは、phpコマンドを省略してDrupal Consoleを使うことができる唯一の方法だからです。

## Git Bash プロンプトでcurlを使用する:
```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
```
## もしくは、コマンドプロンプトで以下のコマンドを実行する:
```
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar
```

php.exeがPATH環境変数で設定されたパス上にあれば、これで実行することができます。

## Drupal Consoleを実行する:

```
$ php drupal.phar
```

drupal.pharをdrupalにリネームし、php.exeと同じディレクトリにコピーすれば、Git Bash上からphpコマンドを省略して実行する事ができます。

#### Drupal Consoleを実行する:
```
$ drupal
```

**備考:** `drupal` という名前は単なるエイリアスなので、別の名前にすることもできます。
