# generate:entity:config
Генерирует сущность конфигурации

**Использование:**
```
drupal generate:entity:config [options]
gec
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--entity-class | Класс сущности конфигурации
--entity-name | Имя сущности конфигурации
--base-path | Базовые пути для маршрутов сущности конфигурации
--label | Заголовок
--bundle-of | Действовать, как бандл для контент сущностей

## Примеры
* Генерирует сущность конфигурации по имени модуля, классу сущности, имени сущности, пути и заголовку
```
drupal generate:entity:config  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"
```
