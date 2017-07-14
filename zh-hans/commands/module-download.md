# module:download
下载模块

**Usage:**
```
drupal module:download [arguments] [options]
mod
md
```

## Available options
Option | Details
-------|-------------
--path | 贡献项目路径
--latest | 默认下载最新版本
--composer | 使用 Composer 下载模块
--unstable | commands.module.install.options.unstable

## Available arguments
Argument | Details
---------|-------------
module | 要启用的模块之间用空格隔开

## Examples
* Download module specifying module name and its path
```
drupal module:download  modulename  \
  --path="modules/contrib"
```
