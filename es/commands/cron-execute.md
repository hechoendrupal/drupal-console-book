# cron:execute
Ejecutar implementación de cron desde un módulo específico o todos para ejecutar todas las implementaciones

**Uso:**
```
drupal cron:execute [arguments]
croe
cre
```

## Argumentos disponibles
Argumento | Detalles
---------|-------------
module | Nombre del módulo.

## Ejemplos
* Executar el cron globalmente
```
drupal cron:execute
```
* Ejecutar el cron en el módulo especificado
```
drupal cron:execute \
  <module>
```
