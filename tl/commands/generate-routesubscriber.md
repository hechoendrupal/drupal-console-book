# generate:routesubscriber
Generate a RouteSubscriber

**Usage:**
```
drupal generate:routesubscriber [options]
gr
```

## Available options
Option | Details
-------|-------------
--module | The Module name.
--name | Service name
--class | Class name

## Examples
* Generate a route subscriber specifying the module name, the route name and its class
```
drupal generate:routesubscriber  \
  --module="modulename"  \
  --name="modulename.route_subscriber"  \
  --class="RouteSubscriber"
```
