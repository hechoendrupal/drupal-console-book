# generate:event:subscriber
Generează un abonat la eveniment

**Usage:**
```
drupal generate:event:subscriber [options]
ges
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--name | commands.generate.service.options.name
--class | Numele Clasei
--events | Încarcă evenimente din container
--services | Încarcă serviciile din container.

## Examples
* Generate an event subscriber specifying the module name, its name, the class and the events to subscribe
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
