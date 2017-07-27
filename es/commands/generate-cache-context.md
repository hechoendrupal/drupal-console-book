# generate:cache:context
Genera un contexto de caché

**Uso:**
```
drupal generate:cache:context [options]
gcc
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--cache-context | Introduzca el nombre del contexto de caché
--class | Nombre de la clase de contexto de caché
--services | Cargar servicios desde el contenedor.

## Ejemplos
* Generar un contexto de caché especificando el módulo, el nombre de contexto y su clase
```
drupal generate:cache:context  \
    --module="modulename"  \
    --cache-context="ContextName"  \
    --class="DefaultCacheContext"
```
