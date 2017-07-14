# generate:entity:content
Generar una nueva entidad de contenido

**Usage:**
```
drupal generate:entity:content [options]
geco
gect
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--entity-class | Clase de la entidad de contenido
--entity-name | Nombre de la entidad de contenido
--base-path | El directorio raíz para las rutas de la entidad de contenido
--label | Etiqueta
--has-bundles | La entidad tiene bundles
--is-translatable | Entidad de contenido traducible
--revisionable | commands.generate.entity.content.options.revisionable

## Examples
* Generate a content entity specifying the module, the entity class, the entity name, its path and label
```
drupal generate:entity:content  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"
```
* Generate a translatable and revisionable content entity specifying the module, the entity class, the entity name, its path and label
```
drupal generate:entity:content  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"  \
  --is-translatable  \
  --revisionable
```
