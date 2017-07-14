# config:override
Sobreescribir valor de la configuración activa.

**Usage:**
```
drupal config:override [arguments]
co
```

## Available arguments
Argument | Details
---------|-------------
name | Nombre de configuración
key | Clave
value | Valor

## Examples
* Definir el valor de "flood" del módulo Contacto a 10.
```
drupal config:override contact.settings flood.limit 10
```
