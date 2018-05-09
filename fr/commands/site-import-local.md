# site:import:local
Importe/Configure un projet local Drupal existant

**Usage:**
```
drupal site:import:local [arguments] [options]
sil
```

## Available options
Option | Details
-------|-------------
--environment | Nom de l'environnement qui qui va être importé

## Available arguments
Argument | Details
---------|-------------
name | Nom qui sera utilisé pour générer la configuration du site
directory | Dossier racine du site Drupal existant

## Examples
* Import local drupal project specifying the site name and the path
```
drupal site:import:local  SiteName /private/var/www/vhost/anexusit/drupal8.dev/web
```
