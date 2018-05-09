# generate:plugin:skeleton
Génère une implémentation d'un squelette de plugin pour les plugins Drupal Console qui n'ont pas de générateur spécifique

**Usage:**
```
drupal generate:plugin:skeleton [options]
gps
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
--plugin-id | L'Id du plugin.
--class | Le nom de la classe du plugin
--services | Charger des services depuis le conteneur.

## Examples
* Generate a plugin skeleton specifying module name, the plugin id and the class
```
drupal generate:plugin:skeleton  \
  --module="modulename"  \
  --plugin-id="link_relation_type"  \
  --class="DefaultLinkRelationType"
```
