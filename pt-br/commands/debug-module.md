# debug:module
Display current modules available for application

**Utilização:**
```
drupal debug:module [arguments] [options]
dm
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--status | Module status [enabled|disabled]
--type | Module type [core|no-core]

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
module | Module name

## Exemplos
* Display all installed modules
```
drupal mod --status=installed
```
* Display all installed and no core modules
```
drupal mod --status=installed --type=no-core
```
