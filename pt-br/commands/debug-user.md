# debug:user
Exibe informações dos usuários da aplicação

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
--roles | Filtrar por papéis
--limit | Limitar quantidade de usuários a serem carregados

## Examples
* Users list on the site
```
drupal debug:user
```
