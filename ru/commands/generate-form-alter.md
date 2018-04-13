# generate:form:alter
Сгенерировать реализацию hook_form_alter() или hook_form_FORM_ID_alter()

**Использование:**
```
drupal generate:form:alter [options]
gfa
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--form-id | Идентификатор формы для внесения изменений
--inputs | Создание полей ввода в форме.

## Примеры
* Сгенерировать hook_form_alter() для пустой формы, указав имя модуля
```
drupal generate:form:alter  \
  --module="modulename"
```
* Сгенерировать hook_form_alter() с двумя полями, указав имя модуля и поля
```
drupal generate:form:alter  \
  --module="modulename"  \
  --inputs='"name":"inputtext", "type":"text_format", "label":"InputText", "options":"", "description":"Just an input text", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'  \
  --inputs='"name":"email", "type":"email", "label":"Email", "options":"", "description":"Just an email input", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'
```
