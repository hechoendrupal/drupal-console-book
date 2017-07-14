# generate:plugin:skeleton
Generar una implementación de un esqueleto de plugin para esos plugins de Drupal Console que no tienen un generador específico

**Usage:**
```
drupal generate:plugin:skeleton [options]
gps
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--plugin-id | commands.generate.plugin.options.plugin-id
--class | Nombre de la clase del plugin
--services | Cargar servicios desde el contenedor.

## Examples
* Generate a plugin skeleton specifying module name, the plugin id and the class
```
drupal generate:plugin:skeleton  \
  --module="modulename"  \
  --plugin-id="link_relation_type"  \
  --class="DefaultLinkRelationType"
```
