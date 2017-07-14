# state:override
Állapotkulcs felülbírálása.

**Usage:**
```
drupal state:override [arguments]
sto
```

## Available arguments
Argument | Details
---------|-------------
key | A felülbírálandó állapotkulcs.
value | A beállítandó állapotkulcs.

## Examples
* Override state value specifying the state name and the new value
```
drupal state:override  comment.node_comment_statistics_scale "!!float 1"
```
