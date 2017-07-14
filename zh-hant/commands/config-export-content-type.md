# config:export:content:type
Export a specific content type and their fields.

**Usage:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## Available options
Option | Details
-------|-------------
--module | The Module name.
--optional-config | Export content type as an optional YAML configuration in your module

## Available arguments
Argument | Details
---------|-------------
content-type | Content Type to be exported

## Examples
* Provide a content type  and module name
```
drupal config:export:content:type page \
  --module="demo"
```
* If you want export content type provide the optional config
```
drupal config:export:content:type page \
  --module="demo" \
  --optional-config
```
