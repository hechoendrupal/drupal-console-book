# state:override
覆写状态键的值

**Usage:**
```
drupal state:override [arguments]
sto
```

## Available arguments
Argument | Details
---------|-------------
key | 覆写的键
value | 赋的新值

## Examples
* Override state value specifying the state name and the new value
```
drupal state:override  comment.node_comment_statistics_scale "!!float 1"
```
