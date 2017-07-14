# node:access:rebuild
Reconstruir los permisos de acceso a nodos. La reconstrucción eliminará todos los privilegios al contenudo y los reemplazará con permisos basado en los módulos y configuración actual,

**Usage:**
```
drupal node:access:rebuild [options]
nar
```

## Available options
Option | Details
-------|-------------
--batch | Procesar en modo batch.

## Examples
* Reconstruir los permisos de acceso a nodos
```
drupal node:access:rebuild --batch
```
