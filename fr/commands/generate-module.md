# generate:module
Génère un module.

**Usage:**
```
drupal generate:module [options]
gm
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module
--machine-name | Le nom machine (minuscules et underscore _ seulement)
--module-path | Le chemin du module
--description | Description du module
--core | Version du cœur.
--package | Paquet <em>package</em> du module
--module-file | Ajouter un fichier .module
--features-bundle | Définir le module en tant que "feature" en précisant le bundle de Features concerné
--composer | Ajouter un fichier composer.json
--dependencies | Dépendances du modules (par exemple : context, galleria, panels)
--test | Générer une classe de test
--twigtemplate | Generate theme template

## Examples
* Generate a module specifying the module name, machine name, the path, its description, drupal core and the package name. In this example the composer file, the unit test and twig template are generated too
```
drupal generate:module  \
  --module="modulename"  \
  --machine-name="modulename"  \
  --module-path="/modules/custom"  \
  --description="My Awesome Module"  \
  --core="8.x"  \
  --package="Custom"  \
  --module-file  \
  --composer  \
  --test  \
  --twigtemplate
```
