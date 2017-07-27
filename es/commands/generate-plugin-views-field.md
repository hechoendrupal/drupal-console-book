# generate:plugin:views:field
Genera un plugin de campo de vista personalizado.

**Uso:**
```
drupal generate:plugin:views:field [options]
gpvf
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del plugin de campo de vista
--title | Views plugin field title Título del plugin de campo de vista
--description | Descripción del plugin de campo de vista

## Ejemplos
* Generar un plugin de campo de vista personalizado especificando el nombre del módulo, la clase, un título y su descripción
```
drupal generate:plugin:views:field  \
  --module="modulename"  \
  --class="CustomViewsField"  \
  --title="Custom views field"  \
  --description="My awesome custom views field plugin."
```
