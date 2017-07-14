# state:override
Override a State key.

**Usage:**
```
drupal state:override [arguments]
sto
```

## Available arguments
Argument | Details
---------|-------------
key | The State key to override.
value | The State value to set.

## Examples
* Override state value specifying the state name and the new value
```
drupal state:override  comment.node_comment_statistics_scale "!!float 1"
```
