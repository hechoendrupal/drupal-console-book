# generate:form
Generate a new form

**Usage:**
```
drupal generate:form [options]
gf
```

## Available options
Option | Details
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

## Examples
* Generate an empty form with config file specifying the module name, the class, a form id and the path
```
drupal generate:form  \
  --module="modulename"  \
  --class="DefaultForm"  \
  --form-id="default_form"  \
  --config-file  \
  --path="/modulename/form/default"
```
* Generate a form with 2 fields and a config file specifying the module name, the class, a form id, the inputs and the path
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
## Field Type Options
You can add fields to the generated form after you see the prompt "New field type (press <return> to stop adding fields) []". When you begin to type in some text, then autocomplete will display the name of a valid field type if there is one available. The valid field types are as follows (this list was generated from testing the field types shown at https://api.drupal.org/api/drupal/elements/8.3.x). 
  
* button
* checkbox
* checkboxes
* color
* datelist
* datetime
* email
* field_ui_table
* fieldset
* file
* hidden
* image_button
* item
* language_select
* machine_name
* managed_file
* number
* password
* password_confirm
* path
* radio
* radios
* range
* search
* select
* submit
* table
* table_select
* tel
* text_format
* text_area
* text_field
* token
* url
* value
* weight
* submit
