# state:override
Sobrescrever a chave de Estado.

**Usage:**
```
drupal state:override [arguments]
sto
```

## Available arguments
Argument | Details
---------|-------------
key | A chave de Estado a ser sobrescrita.
value | O valor do Estado a ser definido.

## Examples
* Override state value specifying the state name and the new value
```
drupal state:override  comment.node_comment_statistics_scale "!!float 1"
```
