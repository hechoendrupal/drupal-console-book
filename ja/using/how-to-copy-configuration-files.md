# 設定ファイルをコピーするには
インストール後に最初に行うべきタスクはinitコマンドです。これは、`~/.console/` ディレクトリにプロジェクトの設定ファイルをコピーします。これらのファイルの設定値を上書きすることで、Drupal Consoleの振る舞いを変更することができます。

 ```
 $ drupal init [--override]
 ```

### `init` コマンドを実行するとコピーされるファイル
```
 ~/.console/
  ├── aliases.yml
  ├── chain
  │   ├── create-data.yml
  │   ├── form-sample.yml
  │   ├── quick-start-mysql.yml
  │   ├── quick-start.yml
  │   ├── sample.yml
  │   ├── site-drop-restore.yml
  │   ├── site-install.yml
  │   └── update-gitbook.yml
  ├── commands.yml
  ├── config.yml
  ├── console.rc
  ├── drupal.fish
  ├── phpcheck.yml
  ├── router.php
  ├── site.mode.yml
  └── sites
      └── sample.yml
```
