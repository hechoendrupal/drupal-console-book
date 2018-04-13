# generate:plugin:imageformatter
Генерирует плагин форматер изображения.

**Использование:**
```
drupal generate:plugin:imageformatter [options]
gpif
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--class | Название класса плагина
--label | Заголовок плагина
--plugin-id | ID плагина

## Примеры
* Генерирует плагин форматер изображения по имени модуля, классу, заголовку и ID плагина
```
drupal generate:plugin:imageformatter  \
  --module="modulename"  \
  --class="ExampleImageFormatter"  \
  --label="Example image formatter"  \
  --plugin-id="example_image_formatter"
```
