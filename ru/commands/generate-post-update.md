# generate:post:update
Генерирует имплементацию hook_post_update_NAME()

**Использование:**
```
drupal generate:post:update [options]
gpu
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--post-update-name | Имя хука после обновления

## Примеры
* Генерирует имплементацию хука после обновления по имени модуля и имени хука после обновления
```
drupal generate:post:update  \
  --module="modulename"  \
  --post-update-name="PostUpdateName"
```
