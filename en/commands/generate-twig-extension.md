# generate:twig:extension
Generate a Twig extension.

**commands.generate.doc.gitbook.messages.usage:**
```
drupal generate:twig:extension [options]
gte
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--name | Twig Extension name
--class | Class name
--services | Load services from the container.

## commands.generate.doc.gitbook.messages.examples
* Generate a twig extension specifying the module name, the extension name and its class
```
drupal generate:twig:extension  \
  --module="modulename"  \
  --name="modulename.twig.extension"  \
  --class="DefaultTwigExtension"
```
