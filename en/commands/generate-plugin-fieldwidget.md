# generate:plugin:fieldwidget
Generate field widget plugin.

**commands.generate.doc.gitbook.messages.usage:**
```
drupal generate:plugin:fieldwidget [options]
gpfw
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin id
--field-type | Field type the plugin can be used with

## commands.generate.doc.gitbook.messages.examples
* Generate a text type field widget plugin specifying the module name, the class, its label, the plugin id and the field type
```
drupal generate:plugin:fieldwidget  \
  --module="modulename"  \
  --class="ExampleFieldWidget"  \
  --label="Example field widget"  \
  --plugin-id="example_field_widget"  \
  --field-type="text"
```
