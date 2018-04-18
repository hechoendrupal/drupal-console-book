# generate:entity:content
Tạo một content entity mới

**Usage:**
```
drupal generate:entity:content [options]
geco
```

## Available options
Option | Details
-------|-------------
--module | Tên module.
--entity-class | Lớp config entity
--entity-name | Tên config entity
--base-path | The base-path for the content entity routes
--label | Nhãn
--has-bundles | Entity có các bundles
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
