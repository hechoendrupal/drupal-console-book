# cron:execute
Ejecutar implementación de cron desde un módulo específico o todos para ejecutar todas las implementaciones

**Usage:**
```
drupal cron:execute [arguments]
croe
cre
```

## Available arguments
Argument | Details
---------|-------------
module | Nombre del módulo.

## Examples
* Execute the cron globally
```
drupal cron:execute
```
* Execute the cron on the specified module
```
drupal cron:execute \
  <module>
```
