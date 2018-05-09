# entity:delete
Supprime une entité spécifique

**Usage:**
```
drupal entity:delete [arguments] [options]
ed
```

## Available options
Option | Details
-------|-------------
--all | Delete all entities of the given type.

## Available arguments
Argument | Details
---------|-------------
entity-definition-id | Id de la définition de l'entité
entity-id | ID de l'entité à supprimer

## Examples
* Delete entity type content using node id
```
drupal entity:delete node 1
```
