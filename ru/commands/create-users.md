# create:users
Создание фиктивных пользователей для Drupal 8.

**application.gitbook.messages.usage:**
```
drupal create:users [arguments] [options]
cru
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | Сколько пользователей вы хотите создать
--password | Пароль, который будет установлен при создании пользователей
--time-range | Как далеко назад во времени пользователи должны быть датированы

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
roles | Роли, которые будут использованы при создании пользователей

## application.gitbook.messages.examples
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
