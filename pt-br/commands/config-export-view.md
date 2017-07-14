# config:export:view
Exportar uma view no formato YAML dentro de um módulo fornecido para reutilização em outro site.

**Usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## Available options
Option | Details
-------|-------------
--module | O nome do módulo.
--optional-config | Exportar view como uma configuração YAML opcional em seu módulo
--include-module-dependencies | Inclua dependências do módulo em um arquivo YAML

## Available arguments
Argument | Details
---------|-------------
view-id | View ID

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
