# generate:form:alter
एक hook_form_alter() या hook_form_FORM_ID_alter कार्यान्वयन उत्पन्न करें

**Usage:**
```
drupal generate:form:alter [options]
gfa
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--form-id | Form ID को बदलने के लिए
--inputs | एक फॉर्म के लिए आदानो को बनाएँ।

## Examples
* Generate a hook form alter for an empty form specifying the module name
```
drupal generate:form:alter  \
  --module="modulename"
```
* Generate a hook form alter with 2 fields specifying the module name and the inputs
```
drupal generate:form:alter  \
  --module="modulename"  \
  --inputs='"name":"inputtext", "type":"text_format", "label":"InputText", "options":"", "description":"Just an input text", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'  \
  --inputs='"name":"email", "type":"email", "label":"Email", "options":"", "description":"Just an email input", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'
```
