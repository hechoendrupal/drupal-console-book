# generate:controller
Generar y registrar un controlador

**Uso:**
```
drupal generate:controller [options]
gcon
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del controlador
--routes | Los enrutamientos, debe ser un array conteniendo [título, método, path]
--services | Cargar servicios desde el contenedor.
--test | Generar una clase de prueba

## Ejemplos
* Generar un controlador especificando el nombre del módulo, la clasee y sus rutas
```
drupal generate:controller  \
  --module="modulename"  \
  --class="DefaultController"  \
  --routes='"title":"ControllerMethod", "name":"modulename.default_controller_hello", "method":"hello", "path":"/modulename/hello/{name}"'  \
  --test
```
