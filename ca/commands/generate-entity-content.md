# generate:entity:content
Generar una entitat de contingut

**Usage:**
```
drupal generate:entity:content [options]
geco
```

## Available options
Option | Details
-------|-------------
--module | Nom del mòdul.
--entity-class | La classe de l'entitat de contingut
--entity-name | El nom de l'entitat de contigut
--base-path | El camí base per les rutes de l'entitat de continguts
--label | Etiqueta
--has-bundles | L'entitat conté bundles
--is-translatable | Content entity translatable
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
