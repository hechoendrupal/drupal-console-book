# debug:module
利用可能なモジュールを表示

**Usage:**
```
drupal debug:module [arguments] [options]
dm
```

## Available options
Option | Details
-------|-------------
--status | モジュールのステータス [enabled|disabled]
--type | モジュールのタイプ [core|no-core]

## Available arguments
Argument | Details
---------|-------------
module | Module name

## Examples
* Display all installed modules
```
drupal mod --status=installed
```
* Display all installed and no core modules
```
drupal mod --status=installed --type=no-core
```
