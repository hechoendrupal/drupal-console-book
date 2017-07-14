# debug:module
显示当前可用模块

**Usage:**
```
drupal debug:module [arguments] [options]
dm
```

## Available options
Option | Details
-------|-------------
--status | 模块状态 [启用|禁用]
--type | 模块类型 [核心|非核心]

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
