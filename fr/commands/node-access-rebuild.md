# node:access:rebuild
Reconstruit les permissions d'accès aux noeuds. Le processus supprimera tous les privilèges sur le contenu et les remplacera par des permissions basés sur les modules et la configuration actuels.

**Usage:**
```
drupal node:access:rebuild [options]
nar
```

## Available options
Option | Details
-------|-------------
--batch | Traiter en mode batch.

## Examples
* Reconstruire les permissions d'accès aux noeuds
```
drupal node:access:rebuild --batch
```
