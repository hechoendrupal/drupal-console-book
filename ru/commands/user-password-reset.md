# user:password:reset
Сброс пароля указанного пользователя.

**Usage:**
```
drupal user:password:reset [arguments]
upr
uspr
```

## Available arguments
Argument | Details
---------|-------------
user | Идентификатор пользователя
password | Пароль в текстовом формате

## Examples
* Update password specifying the user id and the new password
```
drupal user:password:reset  2 p455w0rd
```
