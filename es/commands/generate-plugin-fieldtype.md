# generate:plugin:fieldtype
Genera plugins de tipo de campo.

**Uso:**
```
drupal generate:plugin:fieldtype [options]
gpft
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del plugin
--label | Etiqueta del plugin
--plugin-id | ID del Plugin
--description | Descripción del Plugin
--default-widget | Widget de campo por defecto para este plugin
--default-formatter | Formateador de campo por defecto para este plugin

## Ejemplos
* Generar un plugin de tipo de campo especificando el nombre del módulo, la clase, su etiqueta, el id de plugin y una descripción
```
drupal generate:plugin:fieldtype  \
  --module="modulename"  \
  --class="ExampleFieldType"  \
  --label="Example field type"  \
  --plugin-id="example_field_type"  \
  --description="My Field Type"
```
* Generar un plugin de tipo de campo con un widget por defecto y un formatter especificando el nombre del módulo, la clase, su etiqueta, el id de plugin y una descripción
```
drupal generate:plugin:fieldtype  \
  --module="modulename"  \
  --class="ExampleFieldType"  \
  --label="Example field type"  \
  --plugin-id="example_field_type"  \
  --description="My Field Type"  \
  --default-widget="DefaultWidget"  \
  --default-formatter="DefaultFormatter"
```
