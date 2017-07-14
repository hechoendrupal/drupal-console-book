# config:export:content:type
Экспорт выбранного типа материала и его полей.

**application.gitbook.messages.usage:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | Имя модуля.
--optional-config | Экспорт типа материала как дополнительную YAML конфигурацию в ваш модуль

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
content-type | Тип материала для экспорта

## application.gitbook.messages.examples
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
