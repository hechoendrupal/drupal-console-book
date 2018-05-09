# generate:form:alter
Generar una implementació de hook_form_alter() o hook_form_FORM_ID_alter

**Ús:**
```
drupal generate:form:alter [options]
gfa
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--form-id | Identificador del formulari a alterar
--inputs | Crear camp entrada (input) en un formulari.

## Exemples
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
