# config:override
覆写活动配置

**用法:**
```
$ drupal config:override [arguments]
```

## 可用参数
参数 | 详细
---------|-------------
name | commands.config.override.arguments.name
key | 键
value | 值

## 例子
* 设置 Contact 模块 flood limit 为 10.
```
$ drupal config:override contact.settings flood.limit 10
```
