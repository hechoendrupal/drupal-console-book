# generate:form
नवीन "%s" उत्पन्न करा.

**Usage:**
```
drupal generate:form [options]
gf
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--class | फॉर्म क्लास नाव
--form-id | फॉर्म आयडी
--services | कंटेनर मधून सेवा भरा.
--config-file | एक कॉन्फिग फाइल जोडा.
--inputs | फॉर्म मध्ये इनपुट तयार करा.
--path | फॉर्म पथ प्रविष्ट करा.
--menu-link-gen | मेनू लिंक उत्पन्न करा.
--menu-link-title | मेन्यू लिंकसाठी एक शीर्षक.
--menu-parent | मेनू पालक.
--menu-link-desc | मेन्यू लिंकसाठी एक वर्णन.

## Examples
* Generate an empty form with config file specifying the module name, the class, a form id and the path
```
drupal generate:form  \
  --module="modulename"  \
  --class="DefaultForm"  \
  --form-id="default_form"  \
  --config-file  \
  --path="/modulename/form/default"
```
* Generate a form with 2 fields and a config file specifying the module name, the class, a form id, the inputs and the path
```
drupal generate:form  \
  --module="modulename"  \
  --class="DefaultForm"  \
  --form-id="default_form"  \
  --config-file  \
  --inputs='"name":"inputname", "type":"text_format", "label":"InputName", "options":"", "description":"Just a text input", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'  \
  --inputs='"name":"email", "type":"email", "label":"Email", "options":"", "description":"Just an email input", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'  \
  --path="/modulename/form/default"
```
