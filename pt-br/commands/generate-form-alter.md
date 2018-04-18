# generate:form:alter
Gera uma implementação de hook_form_alter() ou hook_form_FORM_ID_alter

**Utilização:**
```
drupal generate:form:alter [options]
gfa
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--form-id | Form ID para alterar
--inputs | Cria entradas de formulário.

## Exemplos
* Generate a hook form alter for an empty form specifying the module name
```
drupal generate:form:alter  \
  --module="modulename"
```
* Generate a hook form alter with 2 fields specifying the module name and the inputs
```
drupal generate:form:alter  \
  --module="modulename"  \
  --inputs='"name":"inputtext", "type":"text_format", "label":"InputText", "options":"", "description":"Just an input text", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'  \
  --inputs='"name":"email", "type":"email", "label":"Email", "options":"", "description":"Just an email input", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'
```
