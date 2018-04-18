# generate:plugin:migrate:process
Generate a migrate process plugin

**Utilização:**
```
drupal generate:plugin:migrate:process [options]
gpmp
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--class | Plugin class name
--plugin-id | Plugin id

## Exemplos
* Generate a migration plugin process specifying the module name, the class and its id
```
drupal generate:plugin:migrate:process  \
  --module="modulename"  \
  --class="MigrationProcess"  \
  --plugin-id="migrationprocess"
```
