# module:update
更新核心,模块

**Usage:**
```
drupal module:update [arguments] [options]
moup
```

## Available options
Option | Details
-------|-------------
--composer | 使用 Composer 更新模块
--simulate | 使用 Composer 模拟更新模块

## Available arguments
Argument | Details
---------|-------------
module | 模块之间以空格间隔, 留空更新核心以及所有被 Composer 管理的模块

## Examples
* Update module specifying module name and composer parameter
```
drupal module:update  modulename  \
  --composer
```
