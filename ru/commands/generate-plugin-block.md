# generate:plugin:block
Генерирует плагин блока

**Использование:**
```
drupal generate:plugin:block [options]
gpb
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--class | Имя класса плагина
--label | Заголовок плагина
--plugin-id | ID плагина
--theme-region | Регион темы для отображения плагина блока
--inputs | Создание полей ввода в форме.
--services | Загрузка сервисов из контейнера.

## Примеры
* Генерирует плагин блока в регионе header по имени модуля, классу, заголовку, ID, региону и вводу полей
```
drupal generate:plugin:block  \
  --module="modulename"  \
  --class="DefaultBlock"  \
  --label="Default block"  \
  --plugin-id="default_block"  \
  --theme-region="header"  \
  --inputs='"name":"inputtext", "type":"text_format", "label":"InputText", "options":"", "description":"Just an input text", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'
```
