# state:override
Sobrescrever a chave de Estado.

**Utilização:**
```
drupal state:override [arguments]
sto
```

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
key | A chave de Estado a ser sobrescrita.
value | O valor do Estado a ser definido.

## Exemplos
* Override state value specifying the state name and the new value
```
drupal state:override  comment.node_comment_statistics_scale "!!float 1"
```
