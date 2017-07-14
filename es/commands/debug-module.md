# debug:module
Muestra los módulos actualmente disponibles para la aplicación

**application.gitbook.messages.usage:**
```
drupal debug:module [arguments] [options]
dm
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--status | Estado del módulo [installed|uninstalled]
--type | Tipo de módulo [core|no-core]

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
module | Module name

## application.gitbook.messages.examples
* Muestra todos los módulos habilitados
```
drupal mod --status=installed
```
* Muestra todos los módulos habilitados y que no son del core (contrib + custom)
```
drupal mod --status=installed --type=no-core
```
