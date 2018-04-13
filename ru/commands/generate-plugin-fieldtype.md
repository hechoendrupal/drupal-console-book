# generate:plugin:fieldtype
Генерирует плагин типа поля.

**Использование:**
```
drupal generate:plugin:fieldtype [options]
gpft
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--class | Название класса плагина
--label | Заголовок плагина
--plugin-id | ID  плагина
--description | Описание плагина
--default-widget | Виджет по умолчанию для этого типа поля
--default-formatter | Форматтер по умолчанию для этого типа поля

## Примеры
* Генерирует плагин типа поля по имени модуля, классу, заголовку, ID  плагина и описанию
```
drupal generate:plugin:fieldtype  \
  --module="modulename"  \
  --class="ExampleFieldType"  \
  --label="Example field type"  \
  --plugin-id="example_field_type"  \
  --description="My Field Type"
```
* Генерирует плагин типа поля с виджетом и форматтером по умолчанию по имени модуля, классу, заголовку, ID  плагина и описанию
```
drupal generate:plugin:fieldtype  \
  --module="modulename"  \
  --class="ExampleFieldType"  \
  --label="Example field type"  \
  --plugin-id="example_field_type"  \
  --description="My Field Type"  \
  --default-widget="DefaultWidget"  \
  --default-formatter="DefaultFormatter"
```
