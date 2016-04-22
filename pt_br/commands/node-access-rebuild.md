# node:access:rebuild
Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.

**Uso:**
```
$ drupal node:access:rebuild [options]
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--batch | Process in batch mode.

## Exemplos
* Rebuild node access permissions
```
$ drupal node:access:rebuild --batch
```
