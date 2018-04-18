# generate:routesubscriber
生成一个路径订阅

**使用方法:**
```
drupal generate:routesubscriber [options]
gr
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--name | 服务名
--class | 类名

## 例子
* Generate a route subscriber specifying the module name, the route name and its class
```
drupal generate:routesubscriber  \
  --module="modulename"  \
  --name="modulename.route_subscriber"  \
  --class="RouteSubscriber"
```
