# generate:authentication:provider
Hitelesítésszolgáltató létrehozása

**Usage:**
```
drupal generate:authentication:provider [options]
gap
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--class | Hitelesítésszolgáltató osztály
--provider-id | Szolgáltató azonosítója

## Examples
* Generate an authentication provider specifying the module, the class and the provider id
```
drupal generate:authentication:provider  \
  --module="modulename"  \
  --class="DefaultAuthenticationProvider"  \
  --provider-id="default_authentication_provider"
```
