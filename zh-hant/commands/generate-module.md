# generate:module
Generate a module.

**application.gitbook.messages.usage:**
```
drupal generate:module [options]
gm
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | The Module name
--machine-name | The machine name (lowercase and underscore only)
--module-path | The path of the module
--description | Module description
--core | Core version
--package | Module package
--module-file | Add a .module file
--features-bundle | Define module as feature using the given Features bundle name
--composer | Add a composer.json file
--dependencies | Module dependencies separated by commas (i.e. context, panels)
--test | Generate a test class
--twigtemplate | Generate theme template
