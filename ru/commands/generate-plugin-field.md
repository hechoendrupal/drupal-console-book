# generate:plugin:field
Генерирует плагины типа поля, виджета и форматтера

**Использование:**
```
drupal generate:plugin:field [options]
gpf
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--type-class | Название класса плагина типа поля
--type-label | Заголовок плагина типа поля
--type-plugin-id | ID плагина типа поля
--type-description | Описание плагина типа поля
--formatter-class | Название класса плагина форматтера поля
--formatter-label | Заголовок плагина форматтера поля
--formatter-plugin-id | ID плагина форматтера поля
--widget-class | Название класса плагина форматтера поля
--widget-label | Заголовок плагина виджета поля
--widget-plugin-id | ID плагина виджета поля
--field-type | Тип поля с которым плагин форматтера и виджета может быть использован
--default-widget | Плагин виджета по умолчанию для этого типа поля
--default-formatter | Плагин форматтера по умолчанию для этого типа поля

## Примеры
* Генерирует плагины типа поля, виджета и форматтера по имени модуля, типу (класс, заголовок, ID плагина и описание), форматтеру (класс, заголовок, ID плагина и описание) и виджету (класс, заголовок, ID плагина и описание)
```
drupal generate:plugin:field  \
  --module="modulename"  \
  --type-class="ExampleFieldType"  \
  --type-label="Example field type"  \
  --type-plugin-id="example_field_type"  \
  --type-description="My Field Type"  \
  --formatter-class="ExampleFormatterType"  \
  --formatter-label="Example formatter type"  \
  --formatter-plugin-id="example_formatter_type"  \
  --widget-class="ExampleWidgetType"  \
  --widget-label="Example widget type"  \
  --widget-plugin-id="example_widget_type"  \
  --field-type="example_field_type"  \
  --default-widget="example_widget_type"  \
  --default-formatter="example_formatter_type"
```
