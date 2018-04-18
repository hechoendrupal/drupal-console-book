# state:override
Anul·lar l'estat de la clau.

**Usage:**
```
drupal state:override [arguments]
sto
```

## Available arguments
Argument | Details
---------|-------------
key | L'estat de la clau a anul·lar.
value | El valor de l'estat a definir.

## Examples
* Override state value specifying the state name and the new value
```
drupal state:override  comment.node_comment_statistics_scale "!!float 1"
```
