# generate:plugin:migrate:process
Генерирует плагин обработки для миграции

**Использование:**
```
drupal generate:plugin:migrate:process [options]
gpmp
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--class | Имя класса плагина
--plugin-id | ID плагина

## Примеры
* Генерирует плагин обработки для миграции по имени модуля, классу и ID
```
drupal generate:plugin:migrate:process  \
  --module="modulename"  \
  --class="MigrationProcess"  \
  --plugin-id="migrationprocess"
```
