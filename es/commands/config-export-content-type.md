# config:export:content:type
Exporta un tipo de contenido específico y sus campos.

**Usage:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--optional-config | Exportar tipo de contenido como un fichero de configuración YAML opcional en tu módulo

## Available arguments
Argument | Details
---------|-------------
content-type | Tipo de contenido a exportar

## Examples
* Provide a content type  and module name
```
drupal config:export:content:type page \
  --module="demo"
```
* If you want export content type provide the optional config
```
drupal config:export:content:type page \
  --module="demo" \
  --optional-config
```
