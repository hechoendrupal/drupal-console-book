# generate:authentication:provider
Generar un Proveïdor d'Autenticació

**Usage:**
```
drupal generate:authentication:provider [options]
gap
```

## Available options
Option | Details
-------|-------------
--module | Nom del mòdul.
--class | Clase del Proveïdor d'Autenticació
--provider-id | Identificador del proveïdor

## Examples
* Generate an authentication provider specifying the module, the class and the provider id
```
drupal generate:authentication:provider  \
  --module="modulename"  \
  --class="DefaultAuthenticationProvider"  \
  --provider-id="default_authentication_provider"
```
