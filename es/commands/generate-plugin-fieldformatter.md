# generate:plugin:fieldformatter
Genera un plugin de formateador de campo.

**Uso:**
```
drupal generate:plugin:fieldformatter [options]
gpff
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del plugin
--label | Etiqueta del plugin
--plugin-id | ID del plugin
--field-type | Tipo de campo con el que el plugin puede ser usado

## Ejemplos
* Generar un plugin de formateador de campo de texto especificando el nombre del módulo, la clase, la etiqueta, el id de plugin y el tipo de campo
```
drupal generate:plugin:fieldformatter  \
  --module="modulename"  \
  --class="ExampleFieldFormatter"  \
  --label="Example field formatter"  \
  --plugin-id="example_field_formatter"  \
  --field-type="text"
```
