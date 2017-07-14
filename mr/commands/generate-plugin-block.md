# generate:plugin:block
प्लगइन ब्लॉक उत्पन्न करा.

**Usage:**
```
drupal generate:plugin:block [options]
gpb
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन वर्ग नाव
--label | प्लगइन लेबल
--plugin-id | प्लगिन आयडी
--theme-region | प्लगइन रेंडर करण्यासाठी थीम क्षेत्र.
--inputs | फॉर्म मध्ये इनपुट तयार करा.
--services | कंटेनर मधून सेवा भरा.

## Examples
* Generate a plugin block in the header region with an input field specifying the module name, the class, the label, its id, the region and the input
```
drupal generate:plugin:block  \
  --module="modulename"  \
  --class="DefaultBlock"  \
  --label="Default block"  \
  --plugin-id="default_block"  \
  --theme-region="header"  \
  --inputs='"name":"inputtext", "type":"text_format", "label":"InputText", "options":"", "description":"Just an input text", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'
```
