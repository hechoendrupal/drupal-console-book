# generate:entity:content
Генерирует новую контент сущность

**Использование:**
```
drupal generate:entity:content [options]
geco
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--entity-class | Класс контент сущности
--entity-name | Имя контент сущности
--base-path | Базовые пути для маршрутов контент сущности
--label | Заголовок
--has-bundles | Сущность имеет бандла
--is-translatable | Контент сущность поддерживает переводы
--revisionable | commands.generate.entity.content.options.revisionable

## Примеры
* Генерирует контент сущность по имени модуля, классу сущности, имени сущности, пути и заголовку
```
drupal generate:entity:content  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"
```
* Генерирует переводимую контент сущность с поддержкой ревизий по имени модуля, классу сущности, имени сущности, пути и заголовку
```
drupal generate:entity:content  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"  \
  --is-translatable  \
  --revisionable
```
