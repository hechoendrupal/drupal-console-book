# generate:cache:context
Generata un contexto de caché

**Usage:**
```
drupal generate:cache:context [options]
gcc
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--cache-context | Introduzca el nombre del contexto de caché
--class | Nombre de la clase de contexto de caché
--services | Cargar servicios desde el contenedor.

## Examples
* Generate cache for a context specifying the module, the context name and its class
```
drupal generate:cache:context  \
  --module="modulename"  \
  --cache-context="ContextName"  \
  --class="DefaultCacheContext"
```
