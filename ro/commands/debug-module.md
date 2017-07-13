# debug:module
Afişează Modulele curente pentru aplicaţie

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal debug:module [arguments] [options]
$ dm  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--status | Starea Modulului [activat|dezactivat]
--type | Tipul Modulului [core|no-core]

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
module | Module name

## commands.generate.doc.gitbook.messages.examples
* Display all installed modules
```
$ drupal mod --status=installed
```
* Display all installed and no core modules
```
$ drupal mod --status=installed --type=no-core
```
