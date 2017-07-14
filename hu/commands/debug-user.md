# debug:user
Megjeleníti az aktuális felhasználókat

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
--roles | Szerepek szűrése a hibakereséshez
--limit | Hány felhasználó jelenjen meg a hibakeresésben

## Examples
* Users list on the site
```
drupal debug:user
```
