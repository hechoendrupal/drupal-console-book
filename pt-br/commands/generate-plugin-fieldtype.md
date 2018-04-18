# generate:plugin:fieldtype
Gerar um plugin de tipo de campo

**Utilização:**
```
drupal generate:plugin:fieldtype [options]
gpft
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--class | Nome da classe do plugin
--label | Label do plugin
--plugin-id | Id do plugin
--description | Descrição do plugin
--default-widget | Widget de campo padrão deste plugin
--default-formatter | Formatador de campo padrão deste plugin

## Exemplos
* Generate a field type plugin specifying the module name, the class, its label, the plugin id and a description
```
drupal generate:plugin:fieldtype  \
  --module="modulename"  \
  --class="ExampleFieldType"  \
  --label="Example field type"  \
  --plugin-id="example_field_type"  \
  --description="My Field Type"
```
* Generate a field type plugin with a default widget and formatter specifying the module name, the class, its label, the plugin id and a description
```
drupal generate:plugin:fieldtype  \
  --module="modulename"  \
  --class="ExampleFieldType"  \
  --label="Example field type"  \
  --plugin-id="example_field_type"  \
  --description="My Field Type"  \
  --default-widget="DefaultWidget"  \
  --default-formatter="DefaultFormatter"
```
