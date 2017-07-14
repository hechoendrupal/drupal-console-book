# config:diff
Affiche les items de configuration qui sont différents dans la configuration active par rapport à un dossier.

**application.gitbook.messages.usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--reverse | Voir les changements à l'envers (par exemple les différences d'un dossier par rapport à la configuration active).

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
directory | Le dossier à partir duquel comparer. S'il n'est pas renseigné, choisir dans les répertoires de configuration de Drupal.

## application.gitbook.messages.examples
* Provide a config directory
```
drupal config:diff ../config/path
```
