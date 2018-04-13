# generate:plugin:type:yaml
Генерирует тип плагина с Yaml обнаружением

**Использование:**
```
drupal generate:plugin:type:yaml [options]
gpty
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--class | Название класса типа плагина
--plugin-name | Машинное имя типа плагина
--plugin-file-name | Имя файла плагина

## Примеры
* Генерирует плагин с Yaml обнаружением по имени модуля, имени класса, имени плагина и имени файла плагина
```
drupal generate:plugin:type:yaml  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --plugin-name="example_plugin"  \
  --plugin-file-name="example.plugin"
```
