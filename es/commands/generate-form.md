# generate:form
Generate a new "FormBase"

**Uso:**
```
drupal generate:form [options]
gf
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | The Module name.
--class | The form class name
--form-id | The Form id
--services | Load services from the container.
--config-file | Add a config file
--inputs | Create inputs in a form.
--path | Enter the form path
--menu-link-gen | Generate a menu link
--menu-link-title | A title for the menu link
--menu-parent | Menu parent
--menu-link-desc | A description for the menu link

## Ejemplos
* Generar un formulario vacío con un archivo de configuración especificando el nombre del módulo, la clase, id del formulario y la ruta
```
drupal generate:form  \
  --module="modulename"  \
  --class="DefaultForm"  \
  --form-id="default_form"  \
  --config-file  \
  --path="/modulename/form/default"
```
* Generar un formulario con dos campos y un archivo de configuración especificando el nombre del módulo, la clase, el id de formulario, los inputs y la ruta
```
drupal generate:form  \
  --module="modulename"  \
  --class="DefaultForm"  \
  --form-id="default_form"  \
  --config-file  \
  --inputs='"name":"inputname", "type":"text_format", "label":"InputName", "options":"", "description":"Just a text input", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'  \
  --inputs='"name":"email", "type":"email", "label":"Email", "options":"", "description":"Just an email input", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'  \
  --path="/modulename/form/default"
```
