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
user | commands.user.password.reset.options.user
password | Пароль в текстовом формате

## Примеры
* Обновить пароль, указав идентификатор пользователя и новый пароль
```
drupal user:password:reset  2 p455w0rd
```
