# config:export:view
Экспорт представления в YAML формат внутри модуля для повторного использования на другом сайте.

**Usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## Available options
Option | Details
-------|-------------
--module | Имя модуля.
--optional-config | Экспорт представления в модуль как дополнительную YAML конфигурацию
--include-module-dependencies | Включить зависимости модуля в info YAML файл модуля

## Available arguments
Argument | Details
---------|-------------
view-id | ID представления

## Examples
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
