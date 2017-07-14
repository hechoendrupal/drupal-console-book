# generate:plugin:type:annotation
Generate a plugin type with annotation discovery

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal generate:plugin:type:annotation [options]
$ gpta
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--class | Plugin type class name
--machine-name | commands.generate.plugin.type.annotation.options.plugin-id
--label | Plugin type label

## commands.generate.doc.gitbook.messages.examples
* Generate a plugin with annotation discovery specifying module name, class name, machine name and label
```
drupal generate:plugin:type:annotation  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --machine-name="example_plugin"  \
  --label="Example plugin"
```
