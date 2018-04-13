# config:export:view
Экспорт представления в YAML формат внутри модуля для повторного использования на другом сайте.

**Использование:**
```
drupal config:export:view [arguments] [options]
cev
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--optional-config | Экспорт представления в модуль как дополнительную YAML конфигурацию
--include-module-dependencies | Включить зависимости модуля в info YAML файл модуля

## Доступные аргументы
Аргумент | Детали
---------|-------------
view-id | ID представления

## Примеры
* Предоставьте id представления
```
drupal config:export:view viewid
```
* Вы можете предоставить интерактивные значения как параметры.
```
drupal config:export:view viewid \
  --module="modulename" \
  --optional-config \
  --include-module-dependencies
```
