# module:download
Download module or modules in application

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal module:download [arguments] [options]
$ mod  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--path | The path of the contrib project
--latest | Default to download most recent version
--composer | Download the module using Composer
--unstable | commands.module.install.options.unstable

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
module | Module or modules to be enabled should be separated by a space

## commands.generate.doc.gitbook.messages.examples
* Download module specifying module name and its path
```
$ drupal module:download  modulename  \
  --path="modules/contrib"

```
