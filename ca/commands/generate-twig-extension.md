# generate:twig:extension
Generate a Twig extension.

**Ús:**
```
drupal generate:twig:extension [options]
gte
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--name | Twig Extension name
--class | Class name
--services | Carregar serveis des del contenidor.

## Exemples
* Generate a twig extension specifying the module name, the extension name and its class
```
drupal generate:twig:extension  \
  --module="modulename"  \
  --name="modulename.twig.extension"  \
  --class="DefaultTwigExtension"
```
