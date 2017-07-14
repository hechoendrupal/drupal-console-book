# debug:module
Afişează Modulele curente pentru aplicaţie

**application.gitbook.messages.usage:**
```
drupal debug:module [arguments] [options]
dm
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--status | Starea Modulului [activat|dezactivat]
--type | Tipul Modulului [core|no-core]

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
module | Module name

## application.gitbook.messages.examples
* Display all installed modules
```
drupal mod --status=installed
```
* Display all installed and no core modules
```
drupal mod --status=installed --type=no-core
```
