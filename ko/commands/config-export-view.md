# config:export:view
Export a view in YAML format inside a provided module to reuse in other website.

**Usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## Available options
Option | Details
-------|-------------
--module | The Module name.
--optional-config | Export view as an optional YAML configuration in your module
--include-module-dependencies | Include module dependencies in module info YAML file

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
