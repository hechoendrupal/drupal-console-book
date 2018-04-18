# module:download
下载模块

**使用方法:**
```
drupal module:download [arguments] [options]
mod
```

## 可用选项
选项 | 详细信息
-------|-------------
--path | 贡献项目路径
--latest | 默认下载最新版本
--composer | 使用 Composer 下载模块
--unstable | Module unstable

## 可用参数
参数 | 详细信息
---------|-------------
module | 要启用的模块之间用空格隔开

## 例子
* Download module specifying module name and its path
```
drupal module:download  modulename  \
  --path="modules/contrib"
```
