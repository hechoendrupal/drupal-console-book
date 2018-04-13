# generate:plugin:fieldwidget
Генерирует плагин виджета поля.

**Использование:**
```
drupal generate:plugin:fieldwidget [options]
gpfw
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--class | Название класса плагина
--label | Заголовок плагина
--plugin-id | ID  плагина
--field-type | Тип поля с которым плагин может быть использован

## Примеры
* Генерирует плагин текстовый виджет поля по имени модуля, классу, заголовку, ID и типу поля
```
drupal generate:plugin:fieldwidget  \
  --module="modulename"  \
  --class="ExampleFieldWidget"  \
  --label="Example field widget"  \
  --plugin-id="example_field_widget"  \
  --field-type="text"
```
