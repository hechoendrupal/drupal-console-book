# debug:user
Exibe informações dos usuários da aplicação

**Utilização:**
```
drupal debug:user [options]
dus
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--uid | Filters the result list by uids [between quotes separated by spaces]
--username | Filters the result list by usernames [between quotes separated by spaces]
--mail | Filters the result list by user's e-mail [between quotes separated by spaces]
--roles | Filtrar por papéis
--limit | Limitar quantidade de usuários a serem carregados

## Exemplos
* Users list on the site
```
drupal debug:user
```
