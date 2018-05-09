# debug:user
Mostrar els usuaris actuals de l'aplicació

**Ús:**
```
drupal debug:user [options]
dus
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--uid | Filters the result list by uids [between quotes separated by spaces]
--username | Filters the result list by usernames [between quotes separated by spaces]
--mail | Filters the result list by user's e-mail [between quotes separated by spaces]
--roles | Rols per filtrar la depuració
--limit | Quants usuaris voldrieu mostrar

## Exemples
* Users list on the site
```
drupal debug:user
```
