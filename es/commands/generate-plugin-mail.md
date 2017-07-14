# generate:plugin:mail
Genera un plugin de correo

**Usage:**
```
drupal generate:plugin:mail [options]
gpm
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase para el plugin
--label | Etiqueta del plugin
--plugin-id | ID del plugin
--services | Cargar servicios desde el contenedor.

## Examples
* Generate an email plugin specifying the module name, the class, its label and the plugin id
```
drupal generate:plugin:mail  \
  --module="modulename"  \
  --class="HtmlFormatterMail"  \
  --label="Html formatter mail"  \
  --plugin-id="html_formatter_mail"
```
