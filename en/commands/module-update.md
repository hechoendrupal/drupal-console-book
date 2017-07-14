# module:update
Update core, module or modules in the application

**commands.generate.doc.gitbook.messages.usage:**
```
drupal module:update [arguments] [options]
moup
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--composer | Update the module using Composer
--simulate | Simulate the update process with Composer

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
module | Module or modules to be updated should be separated by a space. Leave empty for updating the core and all your modules managed by Composer.

## commands.generate.doc.gitbook.messages.examples
* Update module specifying module name and composer parameter
```
drupal module:update  modulename  \
  --composer
```
