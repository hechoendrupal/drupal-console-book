# debug:database:log
显示应用程序的当前日志事件

**使用方法:**
```
drupal debug:database:log [arguments] [options]
dbb
ws
```

## 可用选项
选项 | 详细信息
-------|-------------
--type | 按特定类型过滤事件
--severity | 按特定级别的严重等级过滤事件
--user-id | 按特定用户 ID 过滤事件
--asc | 按升序列出事件
--limit | 结果限制到特定数字
--offset | 限制的开始位置
--yml | 以 yml 格式打印

## 可用参数
参数 | 详细信息
---------|-------------
event-id | DBLog 事件 ID

## 例子
* 列出日志中的所有条目
```
drupal debug:database:log
```
* 按事件 ID 列出特定的日志条目
```
drupal debug:database:log 21228
```
