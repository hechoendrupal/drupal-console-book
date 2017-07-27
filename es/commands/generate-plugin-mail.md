# generate:plugin:mail
Genera un plugin de correo

**Uso:**
```
drupal generate:plugin:mail [options]
gpm
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase para el plugin
--label | Etiqueta del plugin
--plugin-id | ID del plugin
--services | Cargar servicios desde el contenedor.

## Ejemplos
* Generar un plugin de correo especificando el nombre de módulo, la clase, su etiqueta y el id de plugin
```
drupal generate:plugin:mail  \
  --module="modulename"  \
  --class="HtmlFormatterMail"  \
  --label="Html formatter mail"  \
  --plugin-id="html_formatter_mail"
```
