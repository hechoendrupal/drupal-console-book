# generate:plugin:block
Genera un plugin de bloque

**Usage:**
```
drupal generate:plugin:block [options]
gpb
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del plugin
--label | Etiqueta del plugin
--plugin-id | ID del plugin
--theme-region | Región del tema para renderizar el plugin de bloque
--inputs | Crear campos de entrada en un formulario.
--services | Cargar servicios desde el contenedor.

## Examples
* Generate a plugin block in the header region with an input field specifying the module name, the class, the label, its id, the region and the input
```
drupal generate:plugin:block  \
  --module="modulename"  \
  --class="DefaultBlock"  \
  --label="Default block"  \
  --plugin-id="default_block"  \
  --theme-region="header"  \
  --inputs='"name":"inputtext", "type":"text_format", "label":"InputText", "options":"", "description":"Just an input text", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'
```
