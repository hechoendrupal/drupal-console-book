# entity:delete
Delete an specific entity

**Utilização:**
```
drupal entity:delete [arguments] [options]
ed
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--all | Delete all entities of the given type.

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
entity-definition-id | Entity definition id
entity-id | Entity ID to be deleted

## Exemplos
* Delete entity type content using node id
```
drupal entity:delete node 1
```
