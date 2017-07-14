# module:update
コアやモジュールを更新

**Usage:**
```
drupal module:update [arguments] [options]
moup
```

## Available options
Option | Details
-------|-------------
--composer | Composerを使用してモジュールを更新
--simulate | Composerを使用して更新をシミュレーション

## Available arguments
Argument | Details
---------|-------------
module | アップデートするモジュール名 (複数指定する場合はスペース区切り)。空の場合はComposerで管理されているコアおよび全てのモジュールが対象になります。

## Examples
* Update module specifying module name and composer parameter
```
drupal module:update  modulename  \
  --composer
```
