# debug:module
Az alkalmazáshoz elérhető aktuális modulok megjelenítése

**application.gitbook.messages.usage:**
```
drupal debug:module [arguments] [options]
dm
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--status | Modul állapota [engedélyezett|tiltott]
--type | Modul típusa [alaprendszer|nem alaprendszer]

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
