# site:import:local
Import/Configure an existing local Drupal project

**Ús:**
```
drupal site:import:local [arguments] [options]
sil
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--environment | Name of the environment that is going to be imported

## Arguments disponibles
Argument | Detalls
---------|-------------
name | Name that will be used to generate the site config
directory | Existing Drupal root directory

## Exemples
* Import local drupal project specifying the site name and the path
```
drupal site:import:local  SiteName /private/var/www/vhost/anexusit/drupal8.dev/web
```
