# config:export:content:type
Exportar um tipo de conteúdo específico e os seus campos.

**Usage:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## Available options
Option | Details
-------|-------------
--module | O nome do módulo.
--optional-config | Exportar tipo de conteúdo como um arquivo de configuração YAML opcional em seu módulo.

## Available arguments
Argument | Details
---------|-------------
content-type | Content Type to be exported

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
