# generate:help
Genera una implementación de hook_help()

**Uso:**
```
drupal generate:help [options]
gh
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--description | Descripción del módulo

## Ejemplos
* Generar un hook_help() especificando el nombre del módulo y la descripción
```
drupal generate:help  \
  --module="modulename"  \
  --description="My Awesome Module"
```
