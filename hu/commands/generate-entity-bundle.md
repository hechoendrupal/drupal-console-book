# generate:entity:bundle
Új tartalomtípus létrehozása (tartalom / mezőköteg)

**Usage:**
```
drupal generate:entity:bundle [options]
geb
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--bundle-name | A tartalomtípus programok által használt neve
--bundle-title | A tartalomtípus felhasználók által olvasható neve

## Examples
* Generate bundle entity specifying the module, the bundle name and its title
```
drupal generate:entity:bundle  \
  --module="modulename"  \
  --bundle-name="default"  \
  --bundle-title="default"
```
