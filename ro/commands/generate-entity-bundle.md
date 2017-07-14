# generate:entity:bundle
Generează un tip de conținut nou (nod / entitate)

**Usage:**
```
drupal generate:entity:bundle [options]
geb
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--bundle-name | Numele mașină pentru tipul de conținut
--bundle-title | Numele lizibil pentru tipul de conținut

## Examples
* Generate bundle entity specifying the module, the bundle name and its title
```
drupal generate:entity:bundle  \
  --module="modulename"  \
  --bundle-name="default"  \
  --bundle-title="default"
```
