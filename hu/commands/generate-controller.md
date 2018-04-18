# generate:controller
Kontroller létrehozása és regisztrálása

**Usage:**
```
drupal generate:controller [options]
gcon
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--class | Kontroller osztályneve
--routes | Az útvonalak, [title, method, path] tartalmú tömbnek kell lennie
--services | Szolgáltatások betöltése a tárolóból.
--test | Tesztosztály létrehozása

## Examples
* Generate controller specifying the module name, the class name and its routes
```
drupal generate:controller  \
  --module="modulename"  \
  --class="DefaultController"  \
  --routes='"title":"ControllerMethod", "name":"modulename.default_controller_hello", "method":"hello", "path":"/modulename/hello/{name}"'  \
  --test
```
