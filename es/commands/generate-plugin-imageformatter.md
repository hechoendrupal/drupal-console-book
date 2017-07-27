# generate:plugin:imageformatter
Genera plugins de formateador de imagen.

**Uso:**
```
drupal generate:plugin:imageformatter [options]
gpif
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de clase del plugin
--label | Etiqueta del plugin
--plugin-id | ID del plugin

## Ejemplos
* Generar un plugin de formateador de imagen especificando el nombre del módulo, la clase, su etiqueta y el id de plugin
```
drupal generate:plugin:imageformatter  \
  --module="modulename"  \
  --class="ExampleImageFormatter"  \
  --label="Example image formatter"  \
  --plugin-id="example_image_formatter"
```
