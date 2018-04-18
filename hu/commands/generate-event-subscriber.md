# generate:event:subscriber
Esemény-előfizető létrehozása

**Usage:**
```
drupal generate:event:subscriber [options]
ges
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--name | Service name
--class | Class name
--events | Események betöltése a tárolóból
--services | Szolgáltatások betöltése a tárolóból.

## Examples
* Generate an event subscriber specifying the module name, its name, the class and the events to subscribe
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
