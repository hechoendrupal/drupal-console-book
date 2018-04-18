# user:password:reset
Сброс пароля указанного пользователя.

**Использование:**
```
drupal user:password:reset [arguments]
upr
upsr
```

## Доступные аргументы
Аргумент | Детали
---------|-------------
user | User name/id
password | Пароль в текстовом формате

## Примеры
* Обновить пароль, указав идентификатор пользователя и новый пароль
```
drupal user:password:reset  2 p455w0rd
```
* Update password specifying the user jmolivas and the new password
```
drupal user:password:reset jmolivas p455w0rd
```
