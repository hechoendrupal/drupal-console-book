# generate:cache:context
Generate a cache context

**Ús:**
```
drupal generate:cache:context [options]
gcc
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--cache-context | The cache context name
--class | Cache context class name
--services | Carregar serveis des del contenidor.

## Exemples
* Generate cache for a context specifying the module, the context name and its class
```
drupal generate:cache:context  \
  --module="modulename"  \
  --cache-context="ContextName"  \
  --class="DefaultCacheContext"
```
