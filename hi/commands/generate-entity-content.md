# generate:entity:content
एक नई कंटेंट एंटिटि बनाए

**Usage:**
```
drupal generate:entity:content [options]
geco
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--entity-class | कंटेंट एंटिटि कक्षा
--entity-name | कंटेंट एंटिटि नाम
--base-path | कॉन्फिग एंटिटी रुट्स के लिए बेस पथ
--label | लेबल
--has-bundles | एंटिटि मॆ बंडल हे
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
