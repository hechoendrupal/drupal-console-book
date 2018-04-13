# config:export:single
Экспорт конфигурации в yml файл.

**Использование:**
```
drupal config:export:single [options]
ces
```

## Доступные параметры
Команда | Детали
-------|-------------
--name | commands.config.export.single.options.name
--directory | commands.config.export.arguments.directory
--module | Имя модуля.
--include-dependencies | Экспортировать зависимости конфигурации.
--optional | Экспорт конфигурации как дополнительной YAML конфигурации в вашем модуле
--remove-uuid | Если установлено конфигурация будет экспортирована без uuid ключа.
--remove-config-hash | Если установлено конфигурация будет экспортирована без хеша сайта по умолчанию.

## Примеры
* Предоставление имя настройки конфигурации для экспорта
```
drupal config:export:single \
  --name=config.settings.name
```
* Если указаны опции для uuid и/или хэш конфигурации, то они будут удалены.
```
drupal config:export:single \
  --name=config.settings.name \
  --remove-uuid \
  --remove-config-hash
```
