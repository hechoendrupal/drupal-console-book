# generate:event:subscriber
Generar un subscriptor d'esdeveniments

**Ús:**
```
drupal generate:event:subscriber [options]
ges
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--name | Service name
--class | Class name
--events | Carregar esdeveniments des del contenidor
--services | Carregar serveis des del contenidor.

## Exemples
* Generate an event subscriber specifying the module name, its name, the class and the events to subscribe
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
