# generate:form
Genera un nuevo "FormBase"

**Uso:**
```
drupal generate:form [options]
gf
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | El nombre de la clase del formulario
--form-id | El id del formulario
--services | Cargar servicios desde el contenedor.
--config-file | Añadir un fichero de configuración
--inputs | Crear campos de entrada en un formulario.
--path | Introduzca la ruta del formulario
--menu-link-gen | Generar un enlace de menú
--menu-link-title | Título para el enlace de menú
--menu-parent | Menú padre
--menu-link-desc | Descripción para el enlace de menú

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
