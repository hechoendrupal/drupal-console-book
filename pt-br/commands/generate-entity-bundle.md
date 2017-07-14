# generate:entity:bundle
Gera um novo tipo de conteúdo (node / entity bundle)

**Usage:**
```
drupal generate:entity:bundle [options]
geb
```

## Available options
Option | Details
-------|-------------
--module | O nome do módulo.
--bundle-name | O tipo de conteúdo's nome de máquina
--bundle-title | O nome amigável do tipo de conteúdo

## Examples
* Generate bundle entity specifying the module, the bundle name and its title
```
drupal generate:entity:bundle  \
  --module="modulename"  \
  --bundle-name="default"  \
  --bundle-title="default"
```
