# database:add
添加数据库到 settings.php

**使用方法:**
```
drupal database:add [options]
dba
```

## 可用选项
选项 | 详细信息
-------|-------------
--database | 数据库名称
--username | 数据库用户名
--password | 数据库密码
--prefix | 数据库前缀
--host | 数据库主机地址
--port | 数据库主机端口
--driver | 数据库驱动

## 例子
* 添加数据库到 settings.php
```
drupal database:add \
  --database=DATABASE \
  --username=USERNAME \
  --password=PASSWORD
```
