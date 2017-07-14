# generate:plugin:type:yaml
Generate a plugin type with Yaml discovery

**commands.generate.doc.gitbook.messages.usage:**
```
drupal generate:plugin:type:yaml [options]
gpty
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--class | Plugin type class name
--plugin-name | Plugin type machine name
--plugin-file-name | Plugin file name

## commands.generate.doc.gitbook.messages.examples
* Generate a plugin with Yaml discovery specifying module name, class name, plugin name and plugin file name
```
drupal generate:plugin:type:yaml  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --plugin-name="example_plugin"  \
  --plugin-file-name="example.plugin"
```
