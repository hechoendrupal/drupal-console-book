# config:diff
Affiche les items de configuration qui sont différents dans la configuration active par rapport à un dossier.

**Usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## Available options
Option | Details
-------|-------------
--reverse | Voir les changements à l'envers (par exemple les différences d'un dossier par rapport à la configuration active).

## Available arguments
Argument | Details
---------|-------------
directory | Le dossier à partir duquel comparer. S'il n'est pas renseigné, choisir dans les répertoires de configuration de Drupal.

## Examples
* Provide a config directory
```
drupal config:diff ../config/path
```
