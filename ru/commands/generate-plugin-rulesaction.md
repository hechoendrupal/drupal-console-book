# generate:plugin:rulesaction
Генерирует плагин действия правил

**Использование:**
```
drupal generate:plugin:rulesaction [options]
gpra
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--class | Имя класса плагина
--label | Заголовок плагина
--plugin-id | ID плагина
--type | Тип действия (пользователь или нод)
--category | Категория плагина
--context | Контекст плагина

## Примеры
* Генерирует действие правила типа пользователь по имени модуля, классу, заголовку, ID плагина, типу, категории и контексту
```
drupal generate:plugin:rulesaction  \
  --module="modulename"  \
  --class="DefaultAction"  \
  --label="Default action"  \
  --plugin-id="default_action"  \
  --type="user"  \
  --category="default_action"  \
  --context="default_action"
```
* Генерирует действие правила типа нод по имени модуля, классу, заголовку, ID плагина, типу, категории и контексту
```
drupal generate:plugin:rulesaction  \
  --module="modulename"  \
  --class="DefaultAction"  \
  --label="Default action"  \
  --plugin-id="default_action"  \
  --type="node"  \
  --category="default_action" \
  --context="default_action"
```
