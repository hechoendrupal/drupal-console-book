# generate:routesubscriber
एक RouteSubscriber उत्पन्न करा.

**Usage:**
```
drupal generate:routesubscriber [options]
gr
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--name | सेवेचे नाव
--class | वर्ग नाव

## Examples
* Generate a route subscriber specifying the module name, the route name and its class
```
drupal generate:routesubscriber  \
  --module="modulename"  \
  --name="modulename.route_subscriber"  \
  --class="RouteSubscriber"
```
