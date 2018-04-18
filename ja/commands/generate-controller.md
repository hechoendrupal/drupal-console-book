# generate:controller
Generate & Register a controller

**Usage:**
```
drupal generate:controller [options]
gcon
```

## Available options
Option | Details
-------|-------------
--module | モジュール名
--class | Controller Class name
--routes | The routes, must be an array containing [title, method, path]
--services | コンテナからサービスを読み込む
--test | Generate a test class

## Examples
* Generate controller specifying the module name, the class name and its routes
```
drupal generate:controller  \
  --module="modulename"  \
  --class="DefaultController"  \
  --routes='"title":"ControllerMethod", "name":"modulename.default_controller_hello", "method":"hello", "path":"/modulename/hello/{name}"'  \
  --test
```
