# database:log:poll
轮询看门狗并每 x 秒打印一次新的日志条目

**使用方法:**
```
drupal database:log:poll [arguments] [options]
dblp
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
duration | 在数据库读取之间休眠的持续时间（秒）

## 例子
* 每隔 x 秒在屏幕上打印日志条目
```
drupal database:log:poll \
  100
```
