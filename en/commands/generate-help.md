# generate:help
Generate an implementation of hook_help()

**application.gitbook.messages.usage:**
```
drupal generate:help [options]
gh
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | The Module name.
--description | Module description

## application.gitbook.messages.examples
* Generate a hook help specifying the module name and the description
```
drupal generate:help  \
  --module="modulename"  \
  --description="My Awesome Module"
```
