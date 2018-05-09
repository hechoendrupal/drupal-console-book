# generate:entity:bundle
Generar un nou tipus de contingut (node / entity bundle)

**Ús:**
```
drupal generate:entity:bundle [options]
geb
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--bundle-name | Nom màquina del tipus del contingut
--bundle-title | Nom llegible del tipus de contingut

## Exemples
* Generate bundle entity specifying the module, the bundle name and its title
```
drupal generate:entity:bundle  \
  --module="modulename"  \
  --bundle-name="default"  \
  --bundle-title="default"
```
