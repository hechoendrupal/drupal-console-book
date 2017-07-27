# generate:plugin:skeleton
Generar una implementación de un esqueleto de plugin para esos plugins de Drupal Console que no tienen un generador específico

**Uso:**
```
drupal generate:plugin:skeleton [options]
gps
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--plugin-id | commands.generate.plugin.options.plugin-id
--class | Nombre de la clase del plugin
--services | Cargar servicios desde el contenedor.

## Ejemplos
* Generar un esqueleto de plugin especificando el nombre de módulo, el id de plugin y la clase
```
drupal generate:plugin:skeleton  \
  --module="modulename"  \
  --plugin-id="link_relation_type"  \
  --class="DefaultLinkRelationType"
```
