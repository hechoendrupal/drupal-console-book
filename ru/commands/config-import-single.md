# config:import:single
Импорт выбранной конфигурации.

**Использование:**
```
drupal config:import:single [options]
cis
```

## Доступные параметры
Команда | Детали
-------|-------------
--file | Имена файлов или абсолютные пути к файлам для импорта
--directory | commands.config.import.arguments.directory

## Примеры
* Предоставление опции file для указания полного пути к файлу.
```
drupal config:import:single \
  --file="/path/to/file/block.block.default_block.yml"
```
* Предоставление опций file и directory
```
drupal config:import:single  \
  --file="block.block.default_block.yml" \
  --directory="/path/to/directory"
```
