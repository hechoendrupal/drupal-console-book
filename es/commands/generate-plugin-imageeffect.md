# generate:plugin:imageeffect
Genera un plugin de efecto de imagen.

**Uso:**
```
drupal generate:plugin:imageeffect [options]
gpie
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del plugin
--label | Etiqueta del plugin
--plugin-id | ID del plugin
--description | Descripción del plugin

## Ejemplos
* Generar un plugin de efecto de imagen especificando el nombre de módulo, la clase, su etiqueta, el id de plugin y una descripción
```
drupal generate:plugin:imageeffect  \
  --module="modulename"  \
  --class="DefaultImageEffect"  \
  --label="Default image effect"  \
  --plugin-id="default_image_effect"  \
  --description="My Image Effect"
```
