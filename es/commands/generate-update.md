# generate:update
Generar una implementación de hook_update_N()

**Usage:**
```
drupal generate:update [options]
gu
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--update-n | Número de actualización

## Examples
* Generate an update N hook implementation specifying the module name and the N value
```
drupal generate:update  \
  --module="modulename"  \
  --update-n="8001"
```
