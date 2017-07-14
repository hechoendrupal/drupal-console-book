# generate:authentication:provider
Generate an Authentication Provider

**application.gitbook.messages.usage:**
```
drupal generate:authentication:provider [options]
gap
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | The Module name.
--class | Authentication Provider class
--provider-id | Provider ID

## application.gitbook.messages.examples
* Generate an authentication provider specifying the module, the class and the provider id
```
drupal generate:authentication:provider  \
  --module="modulename"  \
  --class="DefaultAuthenticationProvider"  \
  --provider-id="default_authentication_provider"
```
