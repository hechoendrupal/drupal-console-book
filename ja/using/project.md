# プロジェクトを使う

Drupal Consoleは `stand alone` コマンドと `container aware` コマンドの2種類のコマンドを提供します。

**Stand alone コマンド:**
これらのコマンドはDrupalサイトのルートディレクトリの外側でも実行できます。

**Container aware コマンド:**
これらのコマンドはDrupalサイトのルートディレクトリの中で実行する必要があります。

### Drupalサイトのルートディレクトリの外側でDrupal Consoleを実行する
`--root` オプションを使ってコマンドで利用するDrupalのルートディレクトリを指定すれば、システム上のどこからでもDrupal Consoleを実行できます。

```
$ drupal --root=/var/www/drupal8.dev cr all
```

**備考:** `--root` オプションを指定せずにDrupalサイトのルートディレクトリの外側でDrupal Consoleを実行した場合は、メッセージを受け取ることができます。

Drupalサイトのルートディレクトリの外側でDrupal Consoleを実行した場合、以下のメッセージが表示されます。
> In order to list all of the available commands, you should run this inside a drupal root directory.

Drupalサイトのルートディレクトリの中でDrupal Consoleを実行したが、サイトがまだインストールされていない場合は、以下のメッセージが表示されます。
> In order to list all of the available commands you should install drupal first.
