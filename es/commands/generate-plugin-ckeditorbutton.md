# generate:plugin:ckeditorbutton
Genera un plugin de botón para CKEditor.

**Uso:**
```
drupal generate:plugin:ckeditorbutton [options]
gpc
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase para el plugin
--label | Etiqueta del plugin
--plugin-id | ID del plugin. NOTA: Este corresponde al nombre del plugin de CKEditor. Es el primer argumento de la función CKEDITOR.plugins.add() en el archivo plugin.js.
--button-name | Nombre del botón. NOTA: Este corresponde al nombre del botón de CKEditor. Son el primer argumento de las funciones editor.ui.addButton() o editor.ui.addRichCombo() en el archivo plugin.js.
--button-icon-path | Ruta del icono o imagen del botón.

## Ejemplos
* Generar un botón de CKEditor especificando el nombre del módulo, la clase, la etiqueta, su id y la ruta del icono
```
drupal generate:plugin:ckeditorbutton  \
  --module="modulename"  \
  --class="DefaultCKEditorButton"  \
  --label="Default ckeditor button"  \
  --plugin-id="default ckeditor button"  \
  --button-name="Default ckeditor button"  \
  --button-icon-path="modules/custom/modulename/js/plugins/default ckeditor button/images/icon.png"
```
