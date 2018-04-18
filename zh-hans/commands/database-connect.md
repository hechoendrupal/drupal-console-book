# database:connect
显示 DB 连接

**使用方法:**
```
drupal database:connect [arguments]
dbco
sqlc
```

## 可用参数
参数 | 详细信息
---------|-------------
database | 来自 settings.php 的数据库键

## 例子
* 连接到指定的数据库，或默认数据库，如果没有传入参数
```
drupal database:connect \
  <database>
```
