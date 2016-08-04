# Composerを使ってDrupal Consoleをインストールする
Composerを使ってプロジェクトをインストールすることができます。

## Composerを使ってDrupal Consoleをグローバルにインストールする:
```
$ composer global require drupal/console:@stable
```

## PATHにバイナリがあるディレクトリを追加する:
```
$ echo "PATH=$PATH:~/.composer/vendor/bin" >> ~/.bash_profile
```

## Drupal Consoleを実行する:
```
$ drupal generate:module
```
