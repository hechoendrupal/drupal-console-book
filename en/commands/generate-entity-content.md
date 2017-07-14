# generate:entity:content
Generate a new content entity

**Usage:**
```
drupal generate:entity:content [options]
geco
```

## Available options
Option | Details
-------|-------------
--module | The Module name.
--entity-class | The content entity class
--entity-name | The content entity name
--base-path | The base-path for the content entity routes
--label | The label
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
