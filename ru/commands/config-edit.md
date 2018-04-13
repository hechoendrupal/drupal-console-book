# config:edit
Редактирование выбранной конфигурации.

**Использование:**
```
drupal config:edit [arguments]
ced
cdit
```

## Доступные аргументы
Аргумент | Детали
---------|-------------
config-name | Имя конфигурации.
editor | Редактор.

## Примеры
* Редактирование cron конфигураций с помощью "vim" (редактор по-умолчанию).
```
drupal config:edit system.cron
```
* Редактирование cron конфигураций с помощью "gedit".
```
drupal config:edit system.cron gedit
```
