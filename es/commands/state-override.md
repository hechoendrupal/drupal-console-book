# state:override
Sobreescribir una clave de Estado.

**Usage:**
```
drupal state:override [arguments]
sto
```

## Available arguments
Argument | Details
---------|-------------
key | La clave de Estado que será sobreescrita.
value | El valor de Estado a establecer.

## Examples
* Override state value specifying the state name and the new value
```
drupal state:override  comment.node_comment_statistics_scale "!!float 1"
```
