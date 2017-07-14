# generate:entity:content
Hasilkan sebuah entitas konten baru

**Usage:**
```
drupal generate:entity:content [options]
geco
gect
```

## Available options
Option | Details
-------|-------------
--module | Nama modul.
--entity-class | Kelas entitas konten
--entity-name | Nama entitas konten
--base-path | Path dasar untuk rute entitas konten
--label | Label
--has-bundles | Entity memiliki bundel
--is-translatable | Entitas konten dapat diterjemahkan
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
