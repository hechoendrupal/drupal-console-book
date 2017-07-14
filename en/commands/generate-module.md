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

## application.gitbook.messages.examples
* Generate a module specifying the module name, machine name, the path, its description, drupal core and the package name. In this example the composer file, the unit test and twig template are generated too
```
drupal generate:module  \
  --module="modulename"  \
  --machine-name="modulename"  \
  --module-path="/modules/custom"  \
  --description="My Awesome Module"  \
  --core="8.x"  \
  --package="Custom"  \
  --module-file  \
  --composer  \
  --test  \
  --twigtemplate
```
