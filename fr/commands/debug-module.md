# debug:module
Affiche les modules actuellement disponibles dans l'application

**application.gitbook.messages.usage:**
```
drupal debug:module [arguments] [options]
dm
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--status | Statut du module [installed|uninstalled]
--type | Type de module [core|no-core]

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
module | Module name

## application.gitbook.messages.examples
* Affiche tous les modules actifs (ou installés)
```
drupal mod --status=installed
```
* Affiche tous les modules actifs qui ne sont pas du core (contrib + custom)
```
drupal mod --status=installed --type=no-core
```
