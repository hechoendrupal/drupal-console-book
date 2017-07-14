# generate:authentication:provider
Generate an Authentication Provider

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal generate:authentication:provider [options]
$ gap
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--class | Authentication Provider class
--provider-id | Provider ID

## commands.generate.doc.gitbook.messages.examples
* Generate an authentication provider specifying the module, the class and the provider id
```
drupal generate:authentication:provider  \
  --module="modulename"  \
  --class="DefaultAuthenticationProvider"  \
  --provider-id="default_authentication_provider"
```
