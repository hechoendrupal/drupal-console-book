# generate:event:subscriber
Generate an event subscriber

**Usage:**
```
drupal generate:event:subscriber [options]
ges
```

## Available options
Option | Details
-------|-------------
--module | Имя модуля.
--name | commands.generate.service.options.name
--class | Имя класса
--events | Загрузить события из контейнера
--services | Загрузка сервисов из контейнера.

## Examples
* Generate an event subscriber specifying the module name, its name, the class and the events to subscribe
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
