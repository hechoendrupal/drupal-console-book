# generate:plugin:rest:resource
Generate plugin rest resource

**Utilização:**
```
drupal generate:plugin:rest:resource [options]
gprr
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--class | Plugin Rest Resource class
--plugin-id | Plugin Rest Resource id
--plugin-label | Plugin Rest Resource Label
--plugin-url | Plugin Rest Resource URL
--plugin-states | Plugin Rest Resource States

## Exemplos
* Generate a rest resource plugin using GET specifying the module name, the class, the plugin id, its label, the target url and the request type
```
drupal generate:plugin:rest:resource  \
  --module="modulename"  \
  --class="DefaultRestResource"  \
  --plugin-id="default_rest_resource"  \
  --plugin-label="Default rest resource"  \
  --plugin-url="http://rest.resources.example.com"  \
  --plugin-states='GET'
```
