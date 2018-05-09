# generate:routesubscriber
Generar una ruta de subcriptor (RouteSubscriber)

**Ús:**
```
drupal generate:routesubscriber [options]
gr
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--name | Nom del servei
--class | Nom de la classe

## Exemples
* Generate a route subscriber specifying the module name, the route name and its class
```
drupal generate:routesubscriber  \
  --module="modulename"  \
  --name="modulename.route_subscriber"  \
  --class="RouteSubscriber"
```
