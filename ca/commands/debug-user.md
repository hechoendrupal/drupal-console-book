# debug:user
Mostrar els usuaris actuals de l'aplicació

**Usage:**
```
drupal debug:user [options]
dus
```

## Available options
Option | Details
-------|-------------
--uid | Filters the result list by uids [between quotes separated by spaces]
--username | Filters the result list by usernames [between quotes separated by spaces]
--mail | Filters the result list by user's e-mail [between quotes separated by spaces]
--roles | Rols per filtrar la depuració
--limit | Quants usuaris voldrieu mostrar

## Examples
* Users list on the site
```
drupal debug:user
```
