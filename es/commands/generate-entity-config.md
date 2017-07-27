# generate:entity:config
Generar una nueva entidad de configuración

**Uso:**
```
drupal generate:entity:config [options]
gec
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--entity-class | Clase de la entidad de configuración
--entity-name | Nombre de la entidad de configuración
--base-path | El directorio raíz para las rutas de la entidad de configuración
--label | Etiqueta
--bundle-of | Actúa como un bundle de entidades de contenido

## Ejemplos
* Generar una entidad de configuración especificando el módulo, la clase de entidad, el nombre de entidad, la ruta y su etiqueta
```
drupal generate:entity:config  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"
```
