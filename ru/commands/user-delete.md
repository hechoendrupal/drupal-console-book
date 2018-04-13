# user:delete
Удалить пользователей из приложения

**Использование:**
```
drupal user:delete [options]
ud
```

## Доступные параметры
Команда | Детали
-------|-------------
--user | commands.user.delete.options.user
--roles | Пользователи с данной ролью будут удалены

## Примеры
* Удалить пользователя с идентефикатором 2 с ролью authenticated
```
drupal user:delete  \
  --user-id="2"
  --roles='authenticated'
```
* Удалить пользователя с идентефикатором 3
```
drupal user:delete  \
  --user-id="3"
```
