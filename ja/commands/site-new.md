# site:new
Drupalプロジェクトを新規作成する

**使い方:**
```
$ drupal site:new [arguments] [options]
$ sn  
```

## 利用可能なオプション
オプション | 詳細
-------|-------------
--latest | Use this option to select automatically the latest version
--composer | Install Drupal with Composer
--unstable | Use this option to download unstable releases. If not used, you only can install stable releases. Do not use this with latest nor version.

## 利用可能な引数
引数 | 詳細
---------|-------------
directory | Drupalをダウンロードするディレクトリ
version | ダウンロードするDrupalのバージョン
