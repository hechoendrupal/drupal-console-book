# generate:update
Generar una implementación de hook_update_N()

**Uso:**
```
drupal generate:update [options]
gu
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--update-n | Número de actualización

## Ejemplos
* Generar una implementación del hook update_N especificando el nombre del módulo y el valor de N
```
drupal generate:update  \
  --module="modulename"  \
  --update-n="8001"
```
