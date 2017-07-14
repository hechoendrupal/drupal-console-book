# state:override
Ghi đè một State key.

**Usage:**
```
drupal state:override [arguments]
sto
```

## Available arguments
Argument | Details
---------|-------------
key | State key được ghi đè.
value | Giá trị State để thiết lập.

## Examples
* Override state value specifying the state name and the new value
```
drupal state:override  comment.node_comment_statistics_scale "!!float 1"
```
