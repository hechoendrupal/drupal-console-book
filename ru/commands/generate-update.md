# generate:update
Генерирует имплементацию hook_update_N()

**Использование:**
```
drupal generate:update [options]
gu
```

## Доступные параметры
Команда | Детали
-------|-------------
--module | Имя модуля.
--update-n | Номер обновления

## Примеры
* Генерирует имплементацию hook update N по имени модуля и значению номера обновления
```
drupal generate:update  \
  --module="modulename"  \
  --update-n="8001"
```
