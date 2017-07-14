# generate:entity:bundle
Genera un nuevo tipo de contenido (nodo / bundle de entidad)

**Usage:**
```
drupal generate:entity:bundle [options]
geb
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--bundle-name | El nombre máquina del tipo de contenido
--bundle-title | El nombre amigable del tipo de contenido

## Examples
* Generate bundle entity specifying the module, the bundle name and its title
```
drupal generate:entity:bundle  \
  --module="modulename"  \
  --bundle-name="default"  \
  --bundle-title="default"
```
