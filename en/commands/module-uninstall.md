# module:uninstall
Uninstall module or modules in the application

**application.gitbook.messages.usage:**
```
drupal module:uninstall [arguments] [options]
mou
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--force | Do you want to ignore dependencies and forcefully uninstall the module?
--composer | Uninstalls the module using Composer

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
module | Module name (press <return> to stop adding modules)

## application.gitbook.messages.examples
* Uninstall the module specifying the module name
```
drupal module:uninstall  modulename
```
