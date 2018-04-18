# database:log:clear
从 DBLog 表中删除事件，过滤器可用

**使用方法:**
```
drupal database:log:clear [arguments] [options]
dblc
```

## 可用选项
选项 | 详细信息
-------|-------------
--type | 按特定类型过滤事件
--severity | 按特定级别的严重等级过滤事件
--user-id | 按特定用户 ID 过滤事件

## 可用参数
参数 | 详细信息
---------|-------------
event-id | DBLog 事件 ID

## 例子
* 从 DBLog 表中清除数据库日志
```
drupal database:log:clear \
  <database>
```
* 使用过滤器从 DBLog 表中清除数据库日志
```
drupal database:log:clear \
  <database> \
  --type=TYPE \
  --severity=SEVERITY
```
