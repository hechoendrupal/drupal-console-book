# generate:authentication:provider
Generate an Authentication Provider

**Usage:**
```
drupal generate:authentication:provider [options]
gap
```

## Available options
Option | Details
-------|-------------
--module | The Module name.
--class | Authentication Provider class
--provider-id | Provider ID

## Examples
* Generate an authentication provider specifying the module, the class and the provider id
```
drupal generate:authentication:provider  \
  --module="modulename"  \
  --class="DefaultAuthenticationProvider"  \
  --provider-id="default_authentication_provider"
```
