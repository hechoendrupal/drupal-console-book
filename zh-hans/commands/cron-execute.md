# cron:execute
执行模块实现的计划任务或执行所有计划任务

**使用方法:**
```
drupal cron:execute [arguments]
croe
cre
```

## 可用参数
参数 | 详细信息
---------|-------------
module | 模块名

## 例子
* 全局执行定时任务
```
drupal cron:execute
```
* 执行指定模块的定时任务
```
drupal cron:execute \
  <module>
```
