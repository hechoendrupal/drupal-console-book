# user:password:reset
Recuperar senha para um usuário específico.

**Utilização:**
```
drupal user:password:reset [arguments]
upr
upsr
```

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
user | User name/id
password | Senha em formato texto

## Exemplos
* Update password specifying the user id and the new password
```
drupal user:password:reset  2 p455w0rd
```
* Update password specifying the user jmolivas and the new password
```
drupal user:password:reset jmolivas p455w0rd
```
