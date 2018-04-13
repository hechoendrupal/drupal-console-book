# generate:plugin:rest:resource
Генерирует плагин rest ресурса

**Использование:**
```
drupal generate:plugin:rest:resource [options]
gprr
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--class | Класс плагин Rest ресурса
--plugin-id | ID плагина Rest ресурса
--plugin-label | Заголовок плагина Rest ресурса
--plugin-url | URL плагина Rest ресурса
--plugin-states | Состояния плагина Rest ресурса

## Примеры
* Генерирует плагин rest ресурса по имени модуля, классу, ID плагина, заголовку, URL и типу запроса
```
drupal generate:plugin:rest:resource  \
  --module="modulename"  \
  --class="DefaultRestResource"  \
  --plugin-id="default_rest_resource"  \
  --plugin-label="Default rest resource"  \
  --plugin-url="http://rest.resources.example.com"  \
  --plugin-states='GET'
```
