# generate:event:subscriber
Hasilkan langganan event

**Usage:**
```
drupal generate:event:subscriber [options]
ges
```

## Available options
Option | Details
-------|-------------
--module | Nama modul.
--name | commands.generate.service.options.name
--class | Class name
--events | Memuat event dari kontainer
--services | Memuat servis dari kontainer.

## Examples
* Generate an event subscriber specifying the module name, its name, the class and the events to subscribe
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
