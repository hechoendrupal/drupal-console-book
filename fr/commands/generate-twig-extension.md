# generate:twig:extension
Génère une extension Twig.

**Usage:**
```
drupal generate:twig:extension [options]
gte
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
--name | Nom de l'extension Twig
--class | Nom de la classe
--services | Charger des services depuis le conteneur.

## Examples
* Generate a twig extension specifying the module name, the extension name and its class
```
drupal generate:twig:extension  \
  --module="modulename"  \
  --name="modulename.twig.extension"  \
  --class="DefaultTwigExtension"
```
