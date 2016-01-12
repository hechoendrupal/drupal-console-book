# database:log:debug
**database:log:debug** 命令 显示程序的当前事件日志

**用法:**
```
$ drupal database:log:debug [arguments] [options] 
```

## 可用选项
选项 | 详细
-------|-------------
--type | 根据类型过滤事件
--severity | 根据严重等级过滤事件
--user-id | 根据用户ID过滤事件
--reverse | Reverse the order of events
--limit | 限制显示的结果数目
--offset | 限制的起始点

## 可用参数
参数 | 详细
---------|-------------
event-id | DBLog事件ID
