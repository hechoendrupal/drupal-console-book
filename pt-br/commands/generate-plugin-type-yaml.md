# generate:plugin:type:yaml
Generate a plugin type with Yaml discovery

**Utilização:**
```
drupal generate:plugin:type:yaml [options]
gpty
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--class | Plugin type class name
--plugin-name | Plugin type machine name
--plugin-file-name | Plugin file name

## Exemplos
* Generate a plugin with Yaml discovery specifying module name, class name, plugin name and plugin file name
```
drupal generate:plugin:type:yaml  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --plugin-name="example_plugin"  \
  --plugin-file-name="example.plugin"
```
