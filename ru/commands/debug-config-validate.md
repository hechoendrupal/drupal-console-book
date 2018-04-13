# debug:config:validate
Валидирует схему имплементации перед установкой модуля.

**Использование:**
```
drupal debug:config:validate [arguments] [options]
dcv
```

## Доступные параметры
Команда | Детали
-------|-------------
--schema-name | 

## Доступные аргументы
Аргумент | Детали
---------|-------------
filepath | 
schema-filepath | 

## Примеры
* Валидирует указанную конфигурацию и схему конфигурации
```
drupal debug:config:validate \
  /path/to/file \
  /path/to/schema-filepath
```
