# config:import
Импорт конфигурации в текущее приложение.

**Использование:**
```
drupal config:import [options]
ci
```

## Доступные параметры
Команда | Детали
-------|-------------
--file | Путь к архиву с конфигурацией для импорта.
--directory | Путь к каталогу с конфигурацией для импорта.
--remove-files | Удалить файлы после синхронизации.
--skip-uuid | commands.config.import.options.skip-uuid

## Примеры
* Предоставление файла с конфигурацией
```
drupal config:import \
  --file=/path/to/config/file
```
* Предоставление каталога с конфигурацией
```
drupal config:import  \
  --directory=/path/to/config/dir
```
