# user:password:reset
Reinicialitzar una contrasenya per un usuari determinat.

**Ús:**
```
drupal user:password:reset [arguments]
upr
upsr
```

## Arguments disponibles
Argument | Detalls
---------|-------------
user | User name/id
password | Contrasenya en text sense format

## Exemples
* Update password specifying the user id and the new password
```
drupal user:password:reset  2 p455w0rd
```
* Update password specifying the user jmolivas and the new password
```
drupal user:password:reset jmolivas p455w0rd
```
