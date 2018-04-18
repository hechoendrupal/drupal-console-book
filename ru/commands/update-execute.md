# update:execute
Выполнить указанный update_N хук в модуле или выполнить все

**Использование:**
```
drupal update:execute [arguments]
upex
updb
```

## Доступные аргументы
Аргумент | Детали
---------|-------------
module | Имя модуля.
update-n | commands.update.execute.options.update-n

## Примеры
* Выполнить все обновления
```
drupal update:execute
```
* Execute updates for system module
```
drupal update:execute system
```
