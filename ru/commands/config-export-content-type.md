# config:export:content:type
Экспорт выбранного типа материала и его полей.

**Usage:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## Available options
Option | Details
-------|-------------
--module | Имя модуля.
--optional-config | Экспорт типа материала как дополнительную YAML конфигурацию в ваш модуль

## Available arguments
Argument | Details
---------|-------------
content-type | Тип материала для экспорта

## Examples
* Provide a content type  and module name
```
drupal config:export:content:type page \
  --module="demo"
```
* If you want export content type provide the optional config
```
drupal config:export:content:type page \
  --module="demo" \
  --optional-config
```
