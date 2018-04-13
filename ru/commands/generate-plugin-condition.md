# generate:plugin:condition
Генерирует плагин условия.

**Использование:**
```
drupal generate:plugin:condition [options]
gpco
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--class | Название класса плагина условия
--label | Заголовок плагина условия
--plugin-id | ID плагина условия
--context-definition-id | ID контекста определения
--context-definition-label | Заголовок контекста определения
--context-definition-required | Контекст определения обязателен (TRUE/FALSE)

## Примеры
* Генерирует плагин условия для сущности нода по имени модуля, классу, заголовку, ID и контексту определения
```
drupal generate:plugin:condition  \
  --module="modulename"  \
  --class="ExampleCondition"  \
  --label="Example condition"  \
  --plugin-id="example_condition"  \
  --context-definition-id="entity:node"  \
  --context-definition-label="node"  \
  --context-definition-required
```
* Генерирует плагин условия для языка по имени модуля, классу, заголовку, ID и контексту определения
```
drupal generate:plugin:condition  \
  --module="modulename"  \
  --class="ExampleCondition"  \
  --label="Example condition"  \
  --plugin-id="example_condition"  \
  --context-definition-id="language"  \
  --context-definition-label="Language"  \
  --context-definition-required
```
* Генерирует плагин условия для роли по имени модуля, классу, заголовку, ID и контексту определения
```
drupal generate:plugin:condition  \
  --module="modulename"  \
  --class="ExampleCondition"  \
  --label="Example condition"  \
  --plugin-id="example_condition"  \
  --context-definition-id="entity:user_role"  \
  --context-definition-label="user_role"  \
  --context-definition-required
```
