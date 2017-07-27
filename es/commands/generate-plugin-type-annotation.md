# generate:plugin:type:annotation
Genera un tipo de plugin con descubrimiento de anotaciones

**Uso:**
```
drupal generate:plugin:type:annotation [options]
gpta
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del tipo de plugin
--machine-name | commands.generate.plugin.type.annotation.options.plugin-id
--label | Etiqueta del tipo de plugin

## Ejemplos
* Generar un plugin con descubrimiento de anotaciones especificando el nombre del módulo, el nombre de la clase, el nombre máquina y la etiqueta
```
drupal generate:plugin:type:annotation  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --machine-name="example_plugin"  \
  --label="Example plugin"
```
