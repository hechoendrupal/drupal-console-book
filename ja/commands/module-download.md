# module:download
モジュールをダウンロード

**Usage:**
```
drupal module:download [arguments] [options]
mod
md
```

## Available options
Option | Details
-------|-------------
--path | プロジェクトのパス
--latest | 最新バージョンをダウンロードする
--composer | Composerを利用してモジュールをダウンロードする
--unstable | commands.module.install.options.unstable

## Available arguments
Argument | Details
---------|-------------
module | モジュール名 (複数指定する場合はスペース区切り)

## Examples
* Download module specifying module name and its path
```
drupal module:download  modulename  \
  --path="modules/contrib"
```
