# database:restore
还原数据库结构和内容。

**使用方法:**
```
drupal database:restore [arguments] [options]
dbr
```

## 可用选项
选项 | 详细信息
-------|-------------
--file | 数据库备份文件文件名

## 可用参数
参数 | 详细信息
---------|-------------
database | 来自 settings.php 的数据库键

## 例子
* 将数据库转储文件还原到默认或指定数据库
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
