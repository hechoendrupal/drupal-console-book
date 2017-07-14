# generate:event:subscriber
Gerar um assinante do evento

**Usage:**
```
drupal generate:event:subscriber [options]
ges
```

## Available options
Option | Details
-------|-------------
--module | O nome do módulo.
--name | commands.generate.service.options.name
--class | Nome da classe
--events | Carrega eventos do container
--services | Carrega serviços do container.

## Examples
* Generate an event subscriber specifying the module name, its name, the class and the events to subscribe
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
