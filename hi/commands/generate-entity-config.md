# generate:entity:config
एक नया कॉन्फिग एंटिटि उत्पन्न करे

**Usage:**
```
drupal generate:entity:config [options]
gec
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--entity-class | कॉन्फिग इकाई वर्ग
--entity-name | कॉन्फिग इकाई नाम
--base-path | कॉन्फिग एंटिटी रुट्स के लिए बेस पथ
--label | लेबल
--bundle-of | कंटेंट एंटिटि के लिए बंडल के रूप में कार्य करता है    

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
