# generate:plugin:block
प्लगिन खंड उत्पन्न करें

**Usage:**
```
drupal generate:plugin:block [options]
gpb
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--class | प्लगिन का क्लास नाम
--label | प्लगिन का उप-शीर्षक
--plugin-id | प्लगिन id
--theme-region | Theme रीजन से प्लगइन ब्लॉक रेंडर करने के लिए
--inputs | एक फॉर्म के लिए आदानो को बनाएँ।
--services | सर्विसेज़ को container से लोड करें।

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
