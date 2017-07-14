# config:export:view
Exporta una vista en formato YAML dentro de un modulo para reutilizar en otro sitio web.

**application.gitbook.messages.usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | Nombre del módulo.
--optional-config | Exportar la vista como una configuración YAML opcional en tu módulo
--include-module-dependencies | Incluir las dependencias del módulo en un fichero YAML

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
view-id | ID de la vista

## application.gitbook.messages.examples
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
