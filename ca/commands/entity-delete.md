# entity:delete
Delete an specific entity

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
entity-definition-id | Entity definition id
entity-id | Entity ID to be deleted

## Examples
* Delete entity type content using node id
```
drupal entity:delete node 1
```
