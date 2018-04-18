# state:override
覆写状态键的值

**使用方法:**
```
drupal state:override [arguments]
sto
```

## 可用参数
参数 | 详细信息
---------|-------------
key | 覆写的键
value | 赋的新值

## 例子
* Override state value specifying the state name and the new value
```
drupal state:override  comment.node_comment_statistics_scale "!!float 1"
```
