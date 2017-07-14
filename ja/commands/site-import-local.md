# site:import:local
Import/Configure an existing local Drupal project

**Usage:**
```
drupal site:import:local [arguments] [options]
sil
```

## Available options
Option | Details
-------|-------------
--environment | Name of the environment that is going to be imported

## Available arguments
Argument | Details
---------|-------------
name | Name that will be used to generate the site config
directory | Existing Drupal root directory

## Examples
* Import local drupal project specifying the site name and the path
```
drupal site:import:local  SiteName /private/var/www/vhost/anexusit/drupal8.dev/web
```
