# generate:plugin:fieldformatter
Gerar um plugin de formato de campo.

**Utilização:**
```
drupal generate:plugin:fieldformatter [options]
gpff
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--class | Nome da classe do plugin
--label | Label do plugin
--plugin-id | Id do plugin
--field-type | Tipo de campo que pode ser usado com o plugin

## Exemplos
* Generate a a text field formatter plugin specifying the module name, the class, the label its plugin id and the field type
```
drupal generate:plugin:fieldformatter  \
  --module="modulename"  \
  --class="ExampleFieldFormatter"  \
  --label="Example field formatter"  \
  --plugin-id="example_field_formatter"  \
  --field-type="text"
```
