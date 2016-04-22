# node:access:rebuild
Reconstruir los permisos de acceso a nodos. La reconstrucción eliminará todos los privilegios al contenudo y los reemplazará con permisos basado en los módulos y configuración actual,

**Uso:**
```
$ drupal node:access:rebuild [options]
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--batch | Procesar en modo batch.

## Ejemplos
* Reconstruir los permisos de acceso a nodos
```
$ drupal node:access:rebuild --batch
```
