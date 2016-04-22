# config:export:view
Exporta una vista en formato YAML dentro de un módulo para ser reutilizado en otro sitio.

**Uso:**
```
$ drupal config:export:view [arguments] [options]
$ cev  
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--optional-config | Exportar la vista como una configuración YAML opcional en su módulo
--include-module-dependencies | Incluir las dependencias del módulo en un archivo YAML de información de módulo

## Argumentos disponibles
Argumento | Detalles
---------|-------------
view-id | ID de la vista
