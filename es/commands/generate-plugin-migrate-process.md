# generate:plugin:migrate:process
Genera un plugin de proceso para migración

**Uso:**
```
drupal generate:plugin:migrate:process [options]
gpmp
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del plugin
--plugin-id | ID del Plugin

## Ejemplos
* Generar un plugin de proceso para migración especificando el nombre de módulo, la clase y su id
```
drupal generate:plugin:migrate:process  \
    --module="modulename"  \
    --class="MigrationProcess"  \
    --plugin-id="migrationprocess"
```
