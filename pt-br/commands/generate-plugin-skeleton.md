# generate:plugin:skeleton
Generate an implementation of a skeleton plugin for those plugins Drupal Console do not have a specific generator

**Utilização:**
```
drupal generate:plugin:skeleton [options]
gps
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--plugin-id | The Plugin Id.
--class | Plugin class name
--services | Carrega serviços do container.

## Exemplos
* Generate a plugin skeleton specifying module name, the plugin id and the class
```
drupal generate:plugin:skeleton  \
  --module="modulename"  \
  --plugin-id="link_relation_type"  \
  --class="DefaultLinkRelationType"
```
