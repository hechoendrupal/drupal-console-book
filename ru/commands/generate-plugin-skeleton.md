# generate:plugin:skeleton
Генерирует имплементацию skeleton плагина для тех плагинов для которых Drupal Console не имеет специального генератора

**Использование:**
```
drupal generate:plugin:skeleton [options]
gps
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--plugin-id | ID плагина.
--class | Имя класса плагина
--services | Загрузка сервисов из контейнера.

## Примеры
* Генерирует skeleton плагин по имени модуля, ID плагина и его классу
```
drupal generate:plugin:skeleton  \
  --module="modulename"  \
  --plugin-id="link_relation_type"  \
  --class="DefaultLinkRelationType"
```
