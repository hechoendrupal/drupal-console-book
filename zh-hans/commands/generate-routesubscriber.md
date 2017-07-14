# generate:routesubscriber
生成一个路径订阅

**Usage:**
```
drupal generate:routesubscriber [options]
gr
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--name | 服务名
--class | 类名

## Examples
* Generate a route subscriber specifying the module name, the route name and its class
```
drupal generate:routesubscriber  \
  --module="modulename"  \
  --name="modulename.route_subscriber"  \
  --class="RouteSubscriber"
```
