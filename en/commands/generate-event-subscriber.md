# generate:event:subscriber
Generate an event subscriber

**application.gitbook.messages.usage:**
```
drupal generate:event:subscriber [options]
ges
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | The Module name.
--name | commands.generate.service.options.name
--class | Class name
--events | Load events from the container
--services | Load services from the container.

## application.gitbook.messages.examples
* Generate an event subscriber specifying the module name, its name, the class and the events to subscribe
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
