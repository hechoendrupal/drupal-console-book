# generate:twig:extension
Generate a Twig extension.

**application.gitbook.messages.usage:**
```
drupal generate:twig:extension [options]
gte
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | The Module name.
--name | Twig Extension name
--class | Class name
--services | Load services from the container.

## application.gitbook.messages.examples
* Generate a twig extension specifying the module name, the extension name and its class
```
drupal generate:twig:extension  \
  --module="modulename"  \
  --name="modulename.twig.extension"  \
  --class="DefaultTwigExtension"
```
