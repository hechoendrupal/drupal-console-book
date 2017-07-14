# config:export:view
Экспорт представления в YAML формат внутри модуля для повторного использования на другом сайте.

**application.gitbook.messages.usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | Имя модуля.
--optional-config | Экспорт представления в модуль как дополнительную YAML конфигурацию
--include-module-dependencies | Включить зависимости модуля в info YAML файл модуля

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
view-id | ID представления

## application.gitbook.messages.examples
* Provide a view id
```
drupal config:export:view viewid
```
* You can provide the interactive values like parameter.
```
drupal config:export:view viewid \
  --module="modulename" \
  --optional-config \
  --include-module-dependencies
```
