# create:users
Создание фиктивных пользователей для Drupal 8.

**Usage:**
```
drupal create:users [arguments] [options]
cru
```

## Available options
Option | Details
-------|-------------
--limit | Сколько пользователей вы хотите создать
--password | Пароль, который будет установлен при создании пользователей
--time-range | Как далеко назад во времени пользователи должны быть датированы

## Available arguments
Argument | Details
---------|-------------
roles | Роли, которые будут использованы при создании пользователей

## Examples
* Provide the user role.
```
drupal create:users role
```
* Provide the number of users to create, password and time range to create.
```
drupal create:users role \
  --limit="5" \
  --password="usersnewpassword" \
  --time-range="1"
```
