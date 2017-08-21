# cache:tag:invalidate
Invalida las etiquetas de caché

**Uso:**
```
drupal cache:tag:invalidate [arguments]
cti
```

## Argumentos disponibles
Argumento | Detalles
---------|-------------
tag | Uno o más etiquetas a invalidar.

## Ejemplos
* Invalidar rutas
```
drupal cti routes
```
* Invalidar un nodo específico
```
drupal cti node:1 node_list
```
