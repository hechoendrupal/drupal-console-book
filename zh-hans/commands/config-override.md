# config:override
覆盖活动配置中的配置值。

**使用方法:**
```
drupal config:override [arguments]
co
```

## 可用参数
参数 | 详细信息
---------|-------------
name | 配置名称
key | 键
value | 值

## 例子
* 将联系人模块的洪水限制设置为 10。
```
drupal config:override contact.settings flood.limit 10
```
