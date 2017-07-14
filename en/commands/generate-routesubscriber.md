# generate:routesubscriber
Generate a RouteSubscriber

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal generate:routesubscriber [options]
$ gr
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--name | Service name
--class | Class name

## commands.generate.doc.gitbook.messages.examples
* Generate a route subscriber specifying the module name, the route name and its class
```
drupal generate:routesubscriber  \
  --module="modulename"  \
  --name="modulename.route_subscriber"  \
  --class="RouteSubscriber"
```
