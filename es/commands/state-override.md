# state:override
Sobreescribir una clave de Estado.

**Uso:**
```
drupal state:override [arguments]
sto
```

## Argumentos disponibles
Argumento | Detalles
---------|-------------
key | La clave de Estado que será sobreescrita.
value | El valor de Estado a establecer.

## Ejemplos
* Sobreescribir el valor de Estado especificando el nombre de Estado y el nuevo valor
```
drupal state:override  comment.node_comment_statistics_scale "!!float 1"
```
