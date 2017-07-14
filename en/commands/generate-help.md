# generate:help
Generate an implementation of hook_help()

**commands.generate.doc.gitbook.messages.usage:**
```
drupal generate:help [options]
gh
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--description | Module description

## commands.generate.doc.gitbook.messages.examples
* Generate a hook help specifying the module name and the description
```
drupal generate:help  \
  --module="modulename"  \
  --description="My Awesome Module"
```
