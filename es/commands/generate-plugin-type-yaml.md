# generate:plugin:type:yaml
Genera un tipo de plugin con descubrimiento YAML

**Uso:**
```
drupal generate:plugin:type:yaml [options]
gpty
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del tipo de plugin
--plugin-name | Nombre máquina del tipo de plugin
--plugin-file-name | Nombre del archivo del plugin

## Ejemplos
* Generar un plugin con desubrimiento Yaml especificando el nombre del módulo, el nombre de la clase, el nombre del plugin y el nombre del archivo de plugin
```
drupal generate:plugin:type:yaml  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --plugin-name="example_plugin"  \
  --plugin-file-name="example.plugin"
```
