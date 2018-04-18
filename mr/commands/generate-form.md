# generate:form
Generate a new "FormBase"

**वापर:**
```
drupal generate:form [options]
gf
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | The Module name.
--class | The form class name
--form-id | The Form id
--services | Load services from the container.
--config-file | Add a config file
--inputs | Create inputs in a form.
--path | Enter the form path
--menu-link-gen | Generate a menu link
--menu-link-title | A title for the menu link
--menu-parent | Menu parent
--menu-link-desc | A description for the menu link

## उदाहरणे
* मॉड्युल नाव, वर्ग, एक फॉर्म आयडी आणि पथ निर्देशीत केलेली संरचना फाइलसह रिक्त फॉर्म बनवा.
```
drupal generate:form  \
  --module="modulename"  \
  --class="DefaultForm"  \
  --form-id="default_form"  \
  --config-file  \
  --path="/modulename/form/default"
```
* मॉडेल नाव, वर्ग, एक फॉर्म आयडी, इनपुट आणि पथ निर्दिष्ट करून 2 फिल्डसह एक फॉर्म आणि एक config फाइल उत्पन्न करा.
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
