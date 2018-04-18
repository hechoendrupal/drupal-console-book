# generate:update
Generate an implementation of hook_update_N()

**Utilização:**
```
drupal generate:update [options]
gu
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--update-n | Update Number

## Exemplos
* Generate an update N hook implementation specifying the module name and the N value
```
drupal generate:update  \
  --module="modulename"  \
  --update-n="8001"
```
