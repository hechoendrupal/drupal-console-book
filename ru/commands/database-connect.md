# database:connect
Показывает соединение с базой данных

**Использование:**
```
drupal database:connect [arguments]
dbco
sqlc
```

## Доступные аргументы
Аргумент | Детали
---------|-------------
database | Ключ базы данных из settings.php

## Примеры
* Устанавливает соединение с указанной базой данных или базой данных по умолчанию, если аргумент не был передан
```
drupal database:connect \
  <database>
```
