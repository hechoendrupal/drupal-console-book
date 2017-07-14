# generate:plugin:type:yaml
Tạo một plugin với Yaml discovery

**Usage:**
```
drupal generate:plugin:type:yaml [options]
gpty
```

## Available options
Option | Details
-------|-------------
--module | Tên module.
--class | Tên lớp kiểu plugin
--plugin-name | Tên máy kiểu plugin
--plugin-file-name | Tên file plugin

## Examples
* Generate a plugin with Yaml discovery specifying module name, class name, plugin name and plugin file name
```
drupal generate:plugin:type:yaml  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --plugin-name="example_plugin"  \
  --plugin-file-name="example.plugin"
```
