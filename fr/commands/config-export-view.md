# config:export:view
Exporte une vue vue dans le format YAML au sein d'un module pour la réutiliser sur un autre site.

**Usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
--optional-config | Exporter la vue dans un module comme une configuration optionnelle dans votre module
--include-module-dependencies | Inclure les dépendances de module dans le fichier info YAML du module

## Available arguments
Argument | Details
---------|-------------
view-id | Identifiant de la vue

## Examples
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
