# generate:plugin:fieldformatter
Генерирует плагин форматтера поля.

**Использование:**
```
drupal generate:plugin:fieldformatter [options]
gpff
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
* Генерирует плагин текстовый форматтер поля по имени модуля, классу, заголовку, ID и типу поля
```
drupal generate:plugin:fieldformatter  \
  --module="modulename"  \
  --class="ExampleFieldFormatter"  \
  --label="Example field formatter"  \
  --plugin-id="example_field_formatter"  \
  --field-type="text"
```
