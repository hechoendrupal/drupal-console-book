# generate:plugin:type:annotation
Tạo một kiểu plugin với annotation discovery

**Usage:**
```
drupal generate:plugin:type:annotation [options]
gpta
```

## Available options
Option | Details
-------|-------------
--module | Tên module.
--class | Nhập tên lớp kiểu plugin
--machine-name | commands.generate.plugin.type.annotation.options.plugin-id
--label | Nhập nhãn kiểu plugin

## Examples
* Generate a plugin with annotation discovery specifying module name, class name, machine name and label
```
drupal generate:plugin:type:annotation  \
  --module="modulename"  \
  --class="ExamplePlugin"  \
  --machine-name="example_plugin"  \
  --label="Example plugin"
```
