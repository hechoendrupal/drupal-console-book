# module:update
Met à jour le cœur, ou bien un ou plusieurs modules de l'application

**Usage:**
```
drupal module:update [arguments] [options]
moup
```

## Available options
Option | Details
-------|-------------
--composer | Mettre à jour le module via Composer
--simulate | Simuler le processus de mise à jour via Composer

## Available arguments
Argument | Details
---------|-------------
module | Le ou les modules à mettre à jour doivent être séparés par un espace. Laisser vide pour mettre à jour le cœur et tous vos modules gérés par Composer.

## Examples
* Update module specifying module name and composer parameter
```
drupal module:update  modulename  \
  --composer
```
