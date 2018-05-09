# state:override
Anul·lar l'estat de la clau.

**Ús:**
```
drupal state:override [arguments]
sto
```

## Arguments disponibles
Argument | Detalls
---------|-------------
key | L'estat de la clau a anul·lar.
value | El valor de l'estat a definir.

## Exemples
* Override state value specifying the state name and the new value
```
drupal state:override  comment.node_comment_statistics_scale "!!float 1"
```
