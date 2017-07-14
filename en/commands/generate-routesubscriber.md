# generate:routesubscriber
Generate a RouteSubscriber

**application.gitbook.messages.usage:**
```
drupal generate:routesubscriber [options]
gr
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | The Module name.
--name | Service name
--class | Class name

## application.gitbook.messages.examples
* Generate a route subscriber specifying the module name, the route name and its class
```
drupal generate:routesubscriber  \
  --module="modulename"  \
  --name="modulename.route_subscriber"  \
  --class="RouteSubscriber"
```
