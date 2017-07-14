# config:export:view
Exporte une vue vue dans le format YAML au sein d'un module pour la réutiliser sur un autre site.

**application.gitbook.messages.usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | Le nom du module.
--optional-config | Exporter la vue dans un module comme une configuration optionnelle dans votre module
--include-module-dependencies | Ajouter les dépendances dans le fichier info YAML du module

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
view-id | Identifiant de la vue

## application.gitbook.messages.examples
* Provide a view id
```
drupal config:export:view viewid
```
* You can provide the interactive values like parameter.
```
drupal config:export:view viewid \
  --module="modulename" \
  --optional-config \
  --include-module-dependencies
```
