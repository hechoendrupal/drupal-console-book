# generate:entity:config
Generar una nueva entidad de configuración

**Usage:**
```
drupal generate:entity:config [options]
gec
gecg
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--entity-class | Clase de la entidad de configuración
--entity-name | Nombre de la entidad de configuración
--base-path | El directorio raíz para las rutas de la entidad de configuración
--label | Etiqueta
--bundle-of | Actúa como un bundle de entidades de contenido

## Examples
* Generate config entity specifying the module, the entity class, the entity name, its path and label
```
drupal generate:entity:config  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"
```
