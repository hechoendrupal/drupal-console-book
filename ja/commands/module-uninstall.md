# module:uninstall
モジュールをアンインストール

**Usage:**
```
drupal module:uninstall [arguments] [options]
mou
```

## Available options
Option | Details
-------|-------------
--force | 依存関係を無視してモジュールを強制的にアンインストールしますか？
--composer | Composerを利用してモジュールをアンインストールする

## Available arguments
Argument | Details
---------|-------------
module | モジュール名を入力してください

## Examples
* Uninstall the module specifying the module name
```
drupal module:uninstall  modulename
```
