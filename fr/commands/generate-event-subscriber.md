# generate:event:subscriber
Génère un abonné à un événement

**Usage:**
```
drupal generate:event:subscriber [options]
ges
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
--name | Service name
--class | Class name
--events | Charger des événements depuis le conteneur.
--services | Charger des services depuis le conteneur.

## Examples
* Generate an event subscriber specifying the module name, its name, the class and the events to subscribe
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
