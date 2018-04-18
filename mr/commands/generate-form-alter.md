# generate:form:alter
Hook_form_alter() किंवा hook_form_FORM_ID_alter चा अंमलबजावणी उत्पन्न करा.

**वापर:**
```
drupal generate:form:alter [options]
gfa
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--form-id | बदलण्यासाठी फॉर्म आयडी.
--inputs | फॉर्म मध्ये इनपुट तयार करा.

## उदाहरणे
* मॉड्यूलचे नाव निर्दिष्ट केलेल्या रिकाम्या फॉर्मसाठी हुक फॉर्म बदलवा.
```
drupal generate:form:alter  \
  --module="modulename"
```
* मॉड्यूलचे नाव आणि आदान हे निर्दिष्ट केलेल्या 2 फील्डसह एक हुक फॉर्म बदलवा.
```
drupal generate:form:alter  \
  --module="modulename"  \
  --inputs='"name":"inputtext", "type":"text_format", "label":"InputText", "options":"", "description":"Just an input text", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'  \
  --inputs='"name":"email", "type":"email", "label":"Email", "options":"", "description":"Just an email input", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'
```
