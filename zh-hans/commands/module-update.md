# module:update
更新核心,模块

**使用方法:**
```
drupal module:update [arguments] [options]
moup
```

## 可用选项
选项 | 详细信息
-------|-------------
--composer | 使用 Composer 更新模块
--simulate | 使用 Composer 模拟更新模块

## 可用参数
参数 | 详细信息
---------|-------------
module | 模块之间以空格间隔, 留空更新核心以及所有被 Composer 管理的模块

## 例子
* Update module specifying module name and composer parameter
```
drupal module:update  modulename  \
  --composer
```
