# generate:plugin:skeleton
Generate an implementation of a skeleton plugin

**Usage:**
```
drupal generate:plugin:skeleton [options]
gps
```

## Available options
Option | Details
-------|-------------
--module | The Module name.
--plugin-id | commands.generate.plugin.options.plugin-id
--class | Plugin class name
--services | Load services from the container.

## Examples
* Generate a plugin skeleton specifying module name, the plugin id and the class
```
drupal generate:plugin:skeleton  \
  --module="modulename"  \
  --plugin-id="link_relation_type"  \
  --class="DefaultLinkRelationType"
```
