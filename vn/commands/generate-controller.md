# generate:controller
Tạo và đăng ký một trình điều khiển

**Usage:**
```
drupal generate:controller [options]
gcon
```

## Available options
Option | Details
-------|-------------
--module | Tên module.
--class | Tên lớp của trình điều khiển
--routes | The routes, must be an array containing [title, method, path]
--services | Nạp các dịch vụ từ container.
--test | Tạo một lớp thử nghiệm

## Examples
* Generate controller specifying the module name, the class name and its routes
```
drupal generate:controller  \
  --module="modulename"  \
  --class="DefaultController"  \
  --routes='"title":"ControllerMethod", "name":"modulename.default_controller_hello", "method":"hello", "path":"/modulename/hello/{name}"'  \
  --test
```
