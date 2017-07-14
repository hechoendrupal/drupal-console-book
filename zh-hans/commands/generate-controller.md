# generate:controller
生成并注册新控制器

**Usage:**
```
drupal generate:controller [options]
gcon
gcn
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--class | 控制器类名
--routes | 路由(s)必须是包含 [title, method, path] 的数组
--services | 从容器中导入服务
--test | 生成一个测试类

## Examples
* Generate controller specifying the module name, the class name and its routes
```
drupal generate:controller  \
  --module="modulename"  \
  --class="DefaultController"  \
  --routes='"title":"ControllerMethod", "name":"modulename.default_controller_hello", "method":"hello", "path":"/modulename/hello/{name}"'  \
  --test
```
