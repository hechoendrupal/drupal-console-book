# プロジェクトを更新する
Drupal 8は最新の変更との同期を維持するために積極的に開発中です。Drupal Consoleを更新する一番簡単で推奨される方法は、self-update コマンドを使うことです。

## 更新手順はインストール方法に依存する:

### グローバルにインストールし、"drupal" にリネームしている場合:
```
$ drupal self-update
```

### composerを使用してグローバルにインストールしている場合:
```
$ composer global update drupal/console:@stable
```

### ローカルにインストールしている場合 (console.pharをダウンロードしたディレクトリで実行):
```
$ php console.phar self-update
```
