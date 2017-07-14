# generate:plugin:ckeditorbutton
Genera un plugin de botón para CKEditor.

**Usage:**
```
drupal generate:plugin:ckeditorbutton [options]
gpc
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase para el plugin
--label | Etiqueta del plugin
--plugin-id | ID del plugin. NOTA: Este corresponde al nombre del plugin de CKEditor. Es el primer argumento de la función CKEDITOR.plugins.add() en el archivo plugin.js.
--button-name | Nombre del botón. NOTA: Este corresponde al nombre del botón de CKEditor. Son el primer argumento de las funciones editor.ui.addButton() o editor.ui.addRichCombo() en el archivo plugin.js.
--button-icon-path | Ruta del icono o imagen del botón.

## Examples
* Generate CKEditor button specifying the module name, the class, the label, its id, the button name and the icon path
```
drupal generate:plugin:ckeditorbutton  \
  --module="modulename"  \
  --class="DefaultCKEditorButton"  \
  --label="Default ckeditor button"  \
  --plugin-id="default ckeditor button"  \
  --button-name="Default ckeditor button"  \
  --button-icon-path="modules/custom/modulename/js/plugins/default ckeditor button/images/icon.png"
```
