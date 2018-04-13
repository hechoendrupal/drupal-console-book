# generate:plugin:migrate:source
Генерирует плагин ресурса миграции

**Использование:**
```
drupal generate:plugin:migrate:source [options]
gpms
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--class | Имя класс плагина
--plugin-id | ID плагина
--table | Таблица запросов
--alias | Короткий алиас для отссылки к таблице как
--group-by | Поле по которому результаты будут сгрупированны
--fields | Поля для экспорта

## Примеры
* Генерирует плагин ресурса миграции по имени модуля, классу, ID плагина, таблицы и алиасу
```
drupal generate:plugin:migrate:source  \
  --module="modulename"  \
  --class="PluginClassName"  \
  --plugin-id="plugin_class_name"  \
  --table="DefaultTableName"  \
  --alias="D"
```
* Генерирует плагин ресурса миграции для специфичных полей таблицы пользователей по имени модуля, классу, ID плагина, таблицы, алиасу и полям
```
drupal generate:plugin:migrate:source  \
  --module="modulename"  \
  --class="DefaultPluginClass"  \
  --plugin-id="default_plugin_class"  \
  --table="users"  \
  --alias="u"  \
  --fields='"id":"id", "description":"the user id"'  \
  --fields='"id":"username", "description":"the username"'  \
  --fields='"id":"password", "description":"the user password"'  \
  --fields='"id":"email", "description":"the user email"'
```
