# generate:controller
Générer & enregistrer un contrôleur

**Usage:**
```
drupal generate:controller [options]
gcon
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
--class | Nom du contrôleur
--routes | Les routes doivent être des tableaux contenants [title, method, path]
--services | Charger des services depuis le conteneur.
--test | Générer une classe de test

## Examples
* Generate controller specifying the module name, the class name and its routes
```
drupal generate:controller  \
  --module="modulename"  \
  --class="DefaultController"  \
  --routes='"title":"ControllerMethod", "name":"modulename.default_controller_hello", "method":"hello", "path":"/modulename/hello/{name}"'  \
  --test
```
