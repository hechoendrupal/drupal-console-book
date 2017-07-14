# generate:entity:config
नवीन कॉन्फिग संस्था उत्पन्न करा.

**Usage:**
```
drupal generate:entity:config [options]
gec
gecg
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--entity-class | कॉन्फिग संस्था वर्ग.
--entity-name | संरचना अस्तित्व नाव.
--base-path | संरचना अस्तित्व मार्ग साठी बेस-पथ.
--label | लेबल
--bundle-of | सामग्री संस्थांसाठी बंडल म्हणून कार्य.

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
