# node:access:rebuild
Reconstruir los permisos de acceso a nodos. La reconstrucción eliminará todos los privilegios al contenudo y los reemplazará con permisos basado en los módulos y configuración actual,

**application.gitbook.messages.usage:**
```
drupal node:access:rebuild [options]
nar
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--batch | Procesar en modo batch.

## application.gitbook.messages.examples
* Reconstruir los permisos de acceso a nodos
```
drupal node:access:rebuild --batch
```
