# generate:module
Génère un module.

**application.gitbook.messages.usage:**
```
drupal generate:module [options]
gm
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
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
