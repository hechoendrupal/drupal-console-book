# generate:plugin:fieldwidget
Generate field widget plugin.

**Utilização:**
```
drupal generate:plugin:fieldwidget [options]
gpfw
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin id
--field-type | Field type the plugin can be used with

## Exemplos
* Generate a text type field widget plugin specifying the module name, the class, its label, the plugin id and the field type
```
drupal generate:plugin:fieldwidget  \
  --module="modulename"  \
  --class="ExampleFieldWidget"  \
  --label="Example field widget"  \
  --plugin-id="example_field_widget"  \
  --field-type="text"
```
