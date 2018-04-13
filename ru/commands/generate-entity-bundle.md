# generate:entity:bundle
Сгенерировать новый тип контента (бандл ноды / сущности)

**Использование:**
```
drupal generate:entity:bundle [options]
geb
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--bundle-name | Машинное имя типа контента
--bundle-title | Название типа контента

## Примеры
* Сгенерировать бандл сушности, указав модуль, машинное имя бандла и его название
```
drupal generate:entity:bundle  \
  --module="modulename"  \
  --bundle-name="default"  \
  --bundle-title="default"
```
