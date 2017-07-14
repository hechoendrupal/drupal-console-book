# generate:plugin:fieldformatter
Generate field formatter plugin.

**application.gitbook.messages.usage:**
```
drupal generate:plugin:fieldformatter [options]
gpff
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | The Module name.
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin id
--field-type | Field type the plugin can be used with

## application.gitbook.messages.examples
* Generate a a text field formatter plugin specifying the module name, the class, the label its plugin id and the field type
```
drupal generate:plugin:fieldformatter  \
  --module="modulename"  \
  --class="ExampleFieldFormatter"  \
  --label="Example field formatter"  \
  --plugin-id="example_field_formatter"  \
  --field-type="text"
```
