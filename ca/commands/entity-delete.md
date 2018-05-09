# entity:delete
Delete an specific entity

**Ús:**
```
drupal entity:delete [arguments] [options]
ed
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--all | Delete all entities of the given type.

## Arguments disponibles
Argument | Detalls
---------|-------------
entity-definition-id | Entity definition id
entity-id | Entity ID to be deleted

## Exemples
* Delete entity type content using node id
```
drupal entity:delete node 1
```
