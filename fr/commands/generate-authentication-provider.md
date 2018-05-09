# generate:authentication:provider
Générer un système d'authentification

**Usage:**
```
drupal generate:authentication:provider [options]
gap
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
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
