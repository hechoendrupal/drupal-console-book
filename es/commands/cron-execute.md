# cron:execute
Ejecutar implementación de cron desde un módulo específico o todos para ejecutar todas las implementaciones

**Uso:**
```
$ drupal cron:execute [arguments]
$ croe  
$ cre  
```

## Argumentos disponibles
Argumento | Detalles
---------|-------------
module | Nombre del módulo.

## Ejemplos
* Execute the cron globally
```
$ drupal cron:execute

```
* Execute the cron on the specified module
```
$ drupal cron:execute \
  <module>

```
