# generate:entity:bundle
Generate a new content type (node / entity bundle)

**Usage:**
```
drupal generate:entity:bundle [options]
geb
```

## Available options
Option | Details
-------|-------------
--module | The Module name.
--bundle-name | The content type's machine name
--bundle-title | The content type's human-readable name

## Examples
* Generate bundle entity specifying the module, the bundle name and its title
```
drupal generate:entity:bundle  \
  --module="modulename"  \
  --bundle-name="default"  \
  --bundle-title="default"
```
