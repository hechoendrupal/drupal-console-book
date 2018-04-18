# database:dump
转储数据库结构和内容

**使用方法:**
```
drupal database:dump [arguments] [options]
dbdu
```

## 可用选项
选项 | 详细信息
-------|-------------
--file | 数据库备份文件名称
--gz | 如果您希望将 sql 结果文件使用 gzip 压缩，请传递此选项

## 可用参数
参数 | 详细信息
---------|-------------
database | 来自 settings.php 的数据库键

## 例子
* 转储默认数据库或参数指定的数据库
```
drupal database:dump \
  <database>
```
* 以 gz 压缩格式转储
```
drupal database:dump \
  --gz
```
