# generate:plugin:views:field
Generează o extensie custom de views field.

**Usage:**
```
drupal generate:plugin:views:field [options]
gpvf
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--class | Clasa extensiei de views field
--title | Titlul extensiei de views field
--description | Descrierea extensiei de views field

## Examples
* Generate a custom view field plugin specifying the module name, the class, a title and its description
```
drupal generate:plugin:views:field  \
  --module="modulename"  \
  --class="CustomViewsField"  \
  --title="Custom views field"  \
  --description="My awesome custom views field plugin."
```
