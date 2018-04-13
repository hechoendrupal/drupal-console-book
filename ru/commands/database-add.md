# database:add
Добавить базу данных в settings.php

**Использование:**
```
drupal database:add [options]
dba
```

## Доступные параметры
Команда | Детали
-------|-------------
--database | Имя базы данных
--username | Имя пользователя базы данных
--password | Пароль пользователя базы данных
--prefix | Префикс
--host | Адрес хоста базы данных
--port | Порт хоста базы данных
--driver | Драйвер базы данных

## Примеры
* Добавить базу данных в settings.php
```
drupal database:add \
  --database=DATABASE \
  --username=USERNAME \
  --password=PASSWORD
```
