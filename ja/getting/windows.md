# Drupal ConsoleをWindows上にインストール
Drupal ConsoleをWindows上にインストールする方法は2つあります。Git Bashを使う方法とコマンドプロンプトを使う方法です。私達はGit for Windows (以前は msysgit と呼ばれていました)に含まれる Git Bashを使うことを推奨します。これは、phpコマンドを省略してDrupal Consoleを使うことができる唯一の方法だからです。

Git Bash上でDrupal Consoleを使う場合は、以下のパッケージをインストールしてください。

* [Git for Windows](https://git-for-windows.github.io/)
* [Composer](https://github.com/composer/windows-setup)
* [PHP For Windows](http://windows.php.net/download/)
* [sqlite-tools-win32-x86](https://www.sqlite.org/download.html)

### PATH環境変数を更新する

パッケージをインストールした後に、php.exeとsqlite3.exeをPATH環境変数に含める必要があります。
例えば、"PHP For Windows"を"C:\php"に、"sqlite-tools-win32-x86"を"C:\sqlite"にインストールした場合、コマンドプロンプトから以下のように環境変数をセットすることができます。

```
SETX /M PATH "%PATH%;C:\php;C:\sqlite"
```

### php.iniを設定する

Drupal Consoleはいくつかの拡張機能を要求します。php.iniを編集して、以下の拡張機能を有効にしてください。

```
extension=php_gd2.dll
extension=php_pdo_sqlite.dll
extension=php_curl.dll
extension=php_openssl.dll
```

あなたの言語を使用できるように、次の拡張機能を有効にすることをお勧めします。
```
extension=php_intl.dll
extension=php_mbstring.dll
```

#### 証明書を定義する

Git for Windowsから提供される証明書の情報を設定します。
```
curl.cainfo = C:\Program Files\Git\usr\ssl\certs\ca-bundle.crt;
```

### Composerを使ってDrupal Consoleをグローバルにインストールする:
```
$ composer global require drupal/console:@stable
```

### Drupal Consoleを実行する:

```
$ drupal
```

または、利用可能なチェーンの1つであるクイックインストールを行うために、次のコマンドを実行します。
```
$ drupal chain --file="C:\Users\username\.console\chain\quick-start.yml"
```

**NOTE:** `file` オプションは"Windows形式"のパスで指定する必要があります。
