# generate:authentication:provider
Generar un Proveïdor d'Autenticació

**Ús:**
```
drupal generate:authentication:provider [options]
gap
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--class | Clase del Proveïdor d'Autenticació
--provider-id | Identificador del proveïdor

## Exemples
* Generate an authentication provider specifying the module, the class and the provider id
```
drupal generate:authentication:provider  \
  --module="modulename"  \
  --class="DefaultAuthenticationProvider"  \
  --provider-id="default_authentication_provider"
```
