# database:query
直接作为参数执行 SQL 语句

**使用方法:**
```
drupal database:query [arguments] [options]
dbq
sqlq
```

## 可用选项
选项 | 详细信息
-------|-------------
--quick | 不缓存每个查询结果，每接收到一行打印一行
--debug | 当程序退出时打印调试信息，内存和 CPU 使用统计信息
--html | 生成 HTML 输出
--xml | 生成 XML 输出
--raw | 特殊字符不会在输出中转义。
--vertical | 查询的输出以行垂直打印
--batch | 使用 Tab 作为列分隔符打印结果，且每行新起一行。使用此选项，mysql 不使用历史文件

## 可用参数
参数 | 详细信息
---------|-------------
query | 要执行的 SQL 语句
database | 来自 settings.php 的数据库键

## 例子
* 发送数据库查询
```
drupal database:query 'select * from node limit 0,1'
```
