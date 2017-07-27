# generate:authentication:provider
Generar un Proveedor de Autenticación

**Uso:**
```
drupal generate:authentication:provider [options]
gap
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Clase del proveedor de autenticación
--provider-id | ID del proveedor

## Ejemplos
* Generar un proveedor de autenticación especificando el módulo, la clase y el id de proveedor
```
drupal generate:authentication:provider  \
  --module="modulename"  \
  --class="DefaultAuthenticationProvider"  \
  --provider-id="default_authentication_provider"
```
