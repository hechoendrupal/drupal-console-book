# generate:routesubscriber
RouteSubscriber उत्पन्न करे.

**Usage:**
```
drupal generate:routesubscriber [options]
gr
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--name | सेवा का नाम
--class | कक्षा का नाम

## Examples
* Generate a route subscriber specifying the module name, the route name and its class
```
drupal generate:routesubscriber  \
  --module="modulename"  \
  --name="modulename.route_subscriber"  \
  --class="RouteSubscriber"
```
