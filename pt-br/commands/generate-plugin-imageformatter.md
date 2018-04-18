# generate:plugin:imageformatter
Generate image formatter plugin.

**Utilização:**
```
drupal generate:plugin:imageformatter [options]
gpif
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin id

## Exemplos
* Generate a image formatter plugin specifying the module name, the class, its label and the plugin id
```
drupal generate:plugin:imageformatter  \
  --module="modulename"  \
  --class="ExampleImageFormatter"  \
  --label="Example image formatter"  \
  --plugin-id="example_image_formatter"
```
