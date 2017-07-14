# generate:plugin:skeleton
Generate an implementation of a skeleton plugin

**commands.generate.doc.gitbook.messages.usage:**
```
drupal generate:plugin:skeleton [options]
gps
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--plugin-id | commands.generate.plugin.options.plugin-id
--class | Plugin class name
--services | Load services from the container.

## commands.generate.doc.gitbook.messages.examples
* Generate a plugin skeleton specifying module name, the plugin id and the class
```
drupal generate:plugin:skeleton  \
  --module="modulename"  \
  --plugin-id="link_relation_type"  \
  --class="DefaultLinkRelationType"
```
