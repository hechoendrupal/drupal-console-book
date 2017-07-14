# module:update
Update core, module or modules in the application

**application.gitbook.messages.usage:**
```
drupal module:update [arguments] [options]
moup
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--composer | Update the module using Composer
--simulate | Simulate the update process with Composer

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
module | Module or modules to be updated should be separated by a space. Leave empty for updating the core and all your modules managed by Composer.
