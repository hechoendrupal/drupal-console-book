# generate:controller
Generate & Register a controller

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal generate:controller [options]
$ gcon
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--class | Controller Class name
--routes | The routes, must be an array containing [title, method, path]
--services | Load services from the container.
--test | Generate a test class

## commands.generate.doc.gitbook.messages.examples
* Generate controller specifying the module name, the class name and its routes
```
drupal generate:controller  \
  --module="modulename"  \
  --class="DefaultController"  \
  --routes='"title":"ControllerMethod", "name":"modulename.default_controller_hello", "method":"hello", "path":"/modulename/hello/{name}"'  \
  --test
```
