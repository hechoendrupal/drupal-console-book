# generate:controller
Generează și Înregistrează un controller

**Usage:**
```
drupal generate:controller [options]
gcon
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--class | Numele clasei Controller
--routes | The routes, must be an array containing [title, method, path]
--services | Încarcă serviciile din container.
--test | Generați o clasă de test

## Examples
* Generate controller specifying the module name, the class name and its routes
```
drupal generate:controller  \
  --module="modulename"  \
  --class="DefaultController"  \
  --routes='"title":"ControllerMethod", "name":"modulename.default_controller_hello", "method":"hello", "path":"/modulename/hello/{name}"'  \
  --test
```
