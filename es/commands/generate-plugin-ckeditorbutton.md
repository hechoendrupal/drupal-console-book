# generate:plugin:ckeditorbutton
Genera un plugin de botón para CKEditor.

**Uso:**
```
$ drupal generate:plugin:ckeditorbutton [options]
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase para el plugin
--label | Etiqueta del plugin
--plugin-id | ID del plugin. NOTA: Este corresponde al nombre del plugin de CKEditor. Es el primer argumento de la función CKEDITOR.plugins.add() en el archivo plugin.js.
--button-name | Nombre del botón. NOTA: Este corresponde al nombre del botón de CKEditor. Son el primer argumento de las funciones editor.ui.addButton() o editor.ui.addRichCombo() en el archivo plugin.js.
