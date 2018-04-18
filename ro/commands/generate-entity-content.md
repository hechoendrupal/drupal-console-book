# generate:entity:content
Generează o entitate de conținut nouă

**Usage:**
```
drupal generate:entity:content [options]
geco
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--entity-class | Clasa entității de conținut
--entity-name | Numele entității de conținut
--base-path | The base-path for the content entity routes
--label | Eticheta
--has-bundles | Entity has bundles
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
