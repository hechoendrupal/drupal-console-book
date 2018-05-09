# module:uninstall
Désinstalle le ou les modules de l'application

**Usage:**
```
drupal module:uninstall [arguments] [options]
mou
```

## Available options
Option | Details
-------|-------------
--force | Souhaitez-vous ignorer les dépendances et forcer la désinstallation du module ?
--composer | Désinstalle le module via Composer

## Available arguments
Argument | Details
---------|-------------
module | Entrez le nom du module

## Examples
* Uninstall the module specifying the module name
```
drupal module:uninstall  modulename
```
