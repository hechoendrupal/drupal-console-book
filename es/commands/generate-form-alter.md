# generate:form:alter
Genera una implementación de hook_form_alter() o hook_form_FORM_ID_alter

**Uso:**
```
drupal generate:form:alter [options]
gfa
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--form-id | ID del form a alterar
--inputs | Crear campos de entrada en un formulario.

## Ejemplos
* Generar un hook de form_alter para un formulario vacío especificando el nombre del módulo
```
drupal generate:form:alter  \
  --module="modulename"
```
* Generar un hook de form_alter con dos campos especificando el nombre del módulo y los inputs
```
drupal generate:form:alter  \
  --module="modulename"  \
  --inputs='"name":"inputtext", "type":"text_format", "label":"InputText", "options":"", "description":"Just an input text", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'  \
  --inputs='"name":"email", "type":"email", "label":"Email", "options":"", "description":"Just an email input", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'
```
