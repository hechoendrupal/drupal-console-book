# state:override
Surcharge la clé d'un Etat.

**Usage:**
```
drupal state:override [arguments]
sto
```

## Available arguments
Argument | Details
---------|-------------
key | La clé de l'Etat à surcharger.
value | La valeur de l'Etat à fixer.

## Examples
* Override state value specifying the state name and the new value
```
drupal state:override  comment.node_comment_statistics_scale "!!float 1"
```
