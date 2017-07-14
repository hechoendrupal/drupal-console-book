# config:export:view
Exporta una vista en formato YAML dentro de un modulo para reutilizar en otro sitio web.

**Usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--optional-config | Exportar la vista como una configuración YAML opcional en tu módulo
--include-module-dependencies | Incluir las dependencias del módulo en un fichero YAML

## Available arguments
Argument | Details
---------|-------------
view-id | ID de la vista

## Examples
* Provide a view id
```
drupal config:export:view viewid
```
* You can provide the interactive values like parameter.
```
drupal config:export:view viewid \
  --module="modulename" \
  --optional-config \
  --include-module-dependencies
```
