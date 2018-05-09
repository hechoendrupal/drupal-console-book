# generate:plugin:skeleton
Generate an implementation of a skeleton plugin for those plugins Drupal Console do not have a specific generator

**Ús:**
```
drupal generate:plugin:skeleton [options]
gps
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--plugin-id | The Plugin Id.
--class | Plugin class name
--services | Carregar serveis des del contenidor.

## Exemples
* Generate a plugin skeleton specifying module name, the plugin id and the class
```
drupal generate:plugin:skeleton  \
  --module="modulename"  \
  --plugin-id="link_relation_type"  \
  --class="DefaultLinkRelationType"
```
