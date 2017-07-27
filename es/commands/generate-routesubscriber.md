# generate:routesubscriber
Generar un RouteSubscriber

**Uso:**
```
drupal generate:routesubscriber [options]
gr
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--name | Nombre del servicio
--class | Nombre de la clase

## Ejemplos
* Generar un RouteSubscriber especificando el nombre del módulo, el nombre de enrutado y su clase
```
drupal generate:routesubscriber  \
  --module="modulename"  \
  --name="modulename.route_subscriber"  \
  --class="RouteSubscriber"
```
