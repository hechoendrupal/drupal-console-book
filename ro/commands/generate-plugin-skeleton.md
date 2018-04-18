# generate:plugin:skeleton
Generate an implementation of a skeleton plugin for those plugins Drupal Console do not have a specific generator

**Usage:**
```
drupal generate:plugin:skeleton [options]
gps
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--plugin-id | The Plugin Id.
--class | Plugin class name
--services | Încarcă serviciile din container.

## Examples
* Generate a plugin skeleton specifying module name, the plugin id and the class
```
drupal generate:plugin:skeleton  \
  --module="modulename"  \
  --plugin-id="link_relation_type"  \
  --class="DefaultLinkRelationType"
```
