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
--module | The Module name.
--class | Controller Class name
--routes | The routes, must be an array containing [title, method, path]
--services | Load services from the container.
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
