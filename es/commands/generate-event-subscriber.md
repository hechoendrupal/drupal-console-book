# generate:event:subscriber
Genera un suscriptor de eventos

**Uso:**
```
drupal generate:event:subscriber [options]
ges
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--name | commands.generate.service.options.name
--class | Nombre de la clase
--events | Cargar eventos desde el contenedor.
--services | Cargar servicios desde el contenedor.

## Ejemplos
* Generar un suscriptor de eventos especificando el nombre del módulo, su nombre, la clase  r un suscriptor de eventos especificando el nombre del módulo, su nombre, la clase y los eventos a los que suscribirse
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
