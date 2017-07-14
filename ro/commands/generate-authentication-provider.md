# generate:authentication:provider
Generează un "Authentication Provider"

**Usage:**
```
drupal generate:authentication:provider [options]
gap
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--class | commands.generate.authentication.provider.options.class
--provider-id | commands.generate.authentication.provider.options.provider-id

## Examples
* Generate an authentication provider specifying the module, the class and the provider id
```
drupal generate:authentication:provider  \
  --module="modulename"  \
  --class="DefaultAuthenticationProvider"  \
  --provider-id="default_authentication_provider"
```
