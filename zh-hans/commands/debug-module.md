# debug:module
显示可用于应用的当前模块

**使用方法:**
```
drupal debug:module [arguments] [options]
dm
```

## 可用选项
选项 | 详细信息
-------|-------------
--status | 模块状态 [启用|禁用]
--type | 模块类型 [核心|非核心]

## 可用参数
参数 | 详细信息
---------|-------------
module | 模块名称

## 例子
* 显示所有安装的模块
```
drupal mod --status=installed
```
* 显示所有已安装的非核心模块
```
drupal mod --status=installed --type=no-core
```
