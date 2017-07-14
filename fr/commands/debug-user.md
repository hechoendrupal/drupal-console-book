# debug:user
Liste les utilisateurs de l'application

**Usage:**
```
drupal debug:user [options]
dus
```

## Available options
Option | Details
-------|-------------
--uid | Filtre les utilisateurs par uids [entre guillemets séparés par des espaces]
--username | Filtre la liste des résultats par noms d'utilisateur [entre guillemets séparés par des espaces]
--mail | Filtre la liste des résultats par courriels d'utilisateur [entre guillemets séparés par des espaces]
--roles | Fitrer par rôle(s)
--limit | Combien d'utilisateurs voulez-vous afficher

## Examples
* Users list on the site
```
drupal debug:user
```
