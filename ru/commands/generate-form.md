# generate:form
Generate a new "FormBase"

**Использование:**
```
drupal generate:form [options]
gf
```

## Доступные параметры
Команда | Детали
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

## Примеры
* Генерирует пустую форму с config файлом по имени модуля, классу, ID формы и пути
```
drupal generate:form  \
  --module="modulename"  \
  --class="DefaultForm"  \
  --form-id="default_form"  \
  --config-file  \
  --path="/modulename/form/default"
```
* Генерирует форму с двумя полями и config файлом по имени модуля, классу, ID формы, введенным полям и пути
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
