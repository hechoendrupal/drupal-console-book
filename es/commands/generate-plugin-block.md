# generate:plugin:block
Genera un plugin de bloque

**Uso:**
```
drupal generate:plugin:block [options]
gpb
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del plugin
--label | Etiqueta del plugin
--plugin-id | ID del plugin
--theme-region | Región del tema para renderizar el plugin de bloque
--inputs | Crear campos de entrada en un formulario.
--services | Cargar servicios desde el contenedor.

## Ejemplos
* Generar un plugin de bloque en la región de la cabecera con un campo tipo input especificando el nombre del módulo, la clase, la etiqueta, su id, la región y el input
```
drupal generate:plugin:block  \
  --module="modulename"  \
  --class="DefaultBlock"  \
  --label="Default block"  \
  --plugin-id="default_block"  \
  --theme-region="header"  \
  --inputs='"name":"inputtext", "type":"text_format", "label":"InputText", "options":"", "description":"Just an input text", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'
```
