# debug:database:table
显示给定数据库中的所有表。

**使用方法:**
```
drupal debug:database:table [arguments] [options]
ddt
```

## 可用选项
选项 | 详细信息
-------|-------------
--database | 来自 settings.php 的数据库键

## 可用参数
参数 | 详细信息
---------|-------------
table | 调试的表

## 例子
* 显示数据库上的所有表
```
drupal debug:database:table
```
* 显示节点表的字段或参数指定的其他字段
```
drupal debug:database:table node
```
