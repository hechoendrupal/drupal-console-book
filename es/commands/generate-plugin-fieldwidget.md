# generate:plugin:fieldwidget
Genera un plugin de widget de campo.

**Uso:**
```
drupal generate:plugin:fieldwidget [options]
gpfw
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del plugin
--label | Etiqueta del plugin
--plugin-id | ID del plugin
--field-type | Tipo de campo con el que puede ser usado el plugin

## Ejemplos
* Generar un plugin de widget de campo de texto especificando el nombre del módulo, la clase, su etiqueta, el id de plugin y el tipo de campo
```
drupal generate:plugin:fieldwidget  \
  --module="modulename"  \
  --class="ExampleFieldWidget"  \
  --label="Example field widget"  \
  --plugin-id="example_field_widget"  \
  --field-type="text"
```
