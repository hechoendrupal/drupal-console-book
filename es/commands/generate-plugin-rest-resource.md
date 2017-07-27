# generate:plugin:rest:resource
Genera un plugin de recurso rest

**Uso:**
```
drupal generate:plugin:rest:resource [options]
gprr
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del plugin de recurso rest
--name | commands.generate.service.options.name
--plugin-id | ID del plugin de recurso rest
--plugin-label | Etiqueta del plugin de recurso rest
--plugin-url | URL del plugin de recurso rest
--plugin-states | Estados del plugin de recurso rest

## Ejemplos
* Generar un plugin de recurso rest usando GET y especificando el nombre del módulo, la clase, el id de plugin, su etiqueta, la URL de destino y el tipo de peticióel tipo de petición
```
drupal generate:plugin:rest:resource  \
  --module="modulename"  \
  --class="DefaultRestResource"  \
  --plugin-id="default_rest_resource"  \
  --plugin-label="Default rest resource"  \
  --plugin-url="http://rest.resources.example.com"  \
  --plugin-states='GET'
```
