# generate:plugin:views:field
Egyéni nézetmező bővítmény létrehozása.

**Usage:**
```
drupal generate:plugin:views:field [options]
gpvf
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--class | Nézetmező bővítmény osztályneve
--title | Nézetmező bővítmény címe
--description | Nézetmező bővítmény leírása

## Examples
* Generate a custom view field plugin specifying the module name, the class, a title and its description
```
drupal generate:plugin:views:field  \
  --module="modulename"  \
  --class="CustomViewsField"  \
  --title="Custom views field"  \
  --description="My awesome custom views field plugin."
```
