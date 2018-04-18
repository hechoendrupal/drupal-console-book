# generate:routesubscriber
Generar una ruta de subcriptor (RouteSubscriber)

**Usage:**
```
drupal generate:routesubscriber [options]
gr
```

## Available options
Option | Details
-------|-------------
--module | Nom del mòdul.
--name | Nom del servei
--class | Nom de la classe

## Examples
* Generate a route subscriber specifying the module name, the route name and its class
```
drupal generate:routesubscriber  \
  --module="modulename"  \
  --name="modulename.route_subscriber"  \
  --class="RouteSubscriber"
```
