# generate:plugin:views:field
Генерирует плагин поля представления.

**Использование:**
```
drupal generate:plugin:views:field [options]
gpvf
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--class | Имя класса плагина поля представления
--title | Название плагина поля представления
--description | Описание плагина поля представления

## Примеры
* Генерирует новый плагин поля представления по имени модуля, классу, названию и его описанию
```
drupal generate:plugin:views:field  \
  --module="modulename"  \
  --class="CustomViewsField"  \
  --title="Custom views field"  \
  --description="My awesome custom views field plugin."
```
