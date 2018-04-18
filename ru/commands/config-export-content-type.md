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
--remove-uuid | If set, the configuration will be exported without uuid key.
--remove-config-hash | If set, the configuration will be exported without the default site hash key.

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
