# module:download
Télécharge le module ou les modules dans l'application

**Usage:**
```
drupal module:download [arguments] [options]
mod
```

## Available options
Option | Details
-------|-------------
--path | Le chemin du projet contrib
--latest | Valeur par défaut qui télécharge la version la plus récente
--composer | Télécharge le module via Composer
--unstable | Module unstable

## Available arguments
Argument | Details
---------|-------------
module | Le ou les modules à activer doivent être séparés par un espace

## Examples
* Download module specifying module name and its path
```
drupal module:download  modulename  \
  --path="modules/contrib"
```
