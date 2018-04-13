# config:export:content:type
Экспорт выбранного типа материала и его полей.

**Использование:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--optional-config | Экспорт типа материала как дополнительную YAML конфигурацию в ваш модуль
--remove-uuid | commands.config.export.content.type.options.remove-uuid
--remove-config-hash | commands.config.export.content.type.options.remove-config-hash

## Доступные аргументы
Аргумент | Детали
---------|-------------
content-type | Тип материала для экспорта

## Примеры
* Предоставление типа материала и имя модуля
```
drupal config:export:content:type page \
  --module="demo"
```
* Если вы хотите экспортировать тип материала предоставьте дополнительные настройки
```
drupal config:export:content:type page \
  --module="demo" \
  --optional-config
```
