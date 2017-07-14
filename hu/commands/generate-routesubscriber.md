# generate:routesubscriber
RouteSubscriber létrehozása

**Usage:**
```
drupal generate:routesubscriber [options]
gr
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--name | Szolgáltatásnév
--class | Osztálynév

## Examples
* Generate a route subscriber specifying the module name, the route name and its class
```
drupal generate:routesubscriber  \
  --module="modulename"  \
  --name="modulename.route_subscriber"  \
  --class="RouteSubscriber"
```
