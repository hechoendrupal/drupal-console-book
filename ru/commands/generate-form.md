# generate:form
Генерировать новую "FormBase"

**Использование:**
```
drupal generate:form [options]
gf
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--class | Название класса формы
--form-id | Идентификатор формы
--services | Загрузка сервисов из контейнера.
--config-file | Добавить config файл
--inputs | Создание полей ввода в форме.
--path | Введите путь формы
--menu-link-gen | Сгенерировать ссылку в меню
--menu-link-title | Название ссылки в меню
--menu-parent | Родительское меню
--menu-link-desc | Описание ссылки в меню

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
