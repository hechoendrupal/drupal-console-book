# state:override
覆寫系統狀態的鍵名。

**Usage:**
```
drupal state:override [arguments]
sto
```

## Available arguments
Argument | Details
---------|-------------
key | 要覆寫的系統狀態鍵名
value | 要寫入的系統狀態值

## Examples
* Override state value specifying the state name and the new value
```
drupal state:override  comment.node_comment_statistics_scale "!!float 1"
```
