# generate:entity:content
एक नवीन सामग्री संस्था उत्पन्न करा.

**Usage:**
```
drupal generate:entity:content [options]
geco
gect
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--entity-class | सामग्री अस्तित्व श्रेणी.
--entity-name | सामग्री अस्तित्व नाव.
--base-path | सामग्री अस्तित्व मार्गांसाठीचा बेथ-पथ.
--label | लेबल
--has-bundles | अस्तित्वचे समूह आहे.
--is-translatable | सामग्री अस्तित्व भाषांतरयोग्य.
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
