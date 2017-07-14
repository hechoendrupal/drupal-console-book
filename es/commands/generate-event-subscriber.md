# generate:event:subscriber
Genera un suscriptor de eventos

**Usage:**
```
drupal generate:event:subscriber [options]
ges
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--name | commands.generate.service.options.name
--class | Nombre de la clase
--events | Cargar eventos desde el contenedor.
--services | Cargar servicios desde el contenedor.

## Examples
* Generate an event subscriber specifying the module name, its name, the class and the events to subscribe
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
