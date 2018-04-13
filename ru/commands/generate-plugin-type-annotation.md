# generate:plugin:type:annotation
Генерирует тип плагина с обнаружением по аннотации

**Использование:**
```
drupal generate:plugin:type:annotation [options]
gpta
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--class | Название класса типа плагина
--machine-name | commands.generate.plugin.type.annotation.options.plugin-id
--label | Заголовок типа плагина

## Примеры
* Генерирует плагин с обнаружением по аннотации по имени модуля, имени класса, машинному имени и заголовку
```
drupal generate:plugin:type:annotation  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --machine-name="example_plugin"  \
  --label="Example plugin"
```
