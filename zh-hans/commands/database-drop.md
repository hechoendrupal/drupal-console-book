# database:drop
删除给定数据库中的所有表。

**使用方法:**
```
drupal database:drop [arguments]
dbd
```

## 可用参数
参数 | 详细信息
---------|-------------
database | 来自 settings.php 的数据库键

## 例子
* 删除由参数指定的数据库中的表
```
drupal database:drop \
  <database>
```
