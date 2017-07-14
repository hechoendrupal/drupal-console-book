# config:export:view
Export 1 view trong YAML format inside 1 module được cung cấp để sử dụng lại trên các website khác.

**Usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## Available options
Option | Details
-------|-------------
--module | Tên module.
--optional-config | Export view như một lựa chọn YAML configuration trong module của bạn
--include-module-dependencies | Bao gồm module dependencies trong module info YAML file

## Available arguments
Argument | Details
---------|-------------
view-id | View ID

## Examples
* Provide a view id
```
drupal config:export:view viewid
```
* You can provide the interactive values like parameter.
```
drupal config:export:view viewid \
  --module="modulename" \
  --optional-config \
  --include-module-dependencies
```
