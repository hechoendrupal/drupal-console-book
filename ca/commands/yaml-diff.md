# yaml:diff
El comandament **yaml:diff** executa Compare two YAML files in order to find differences between them.

**Ús:**
```
$ drupal yaml:diff [arguments] [options] 
$ yd  
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--stats | Print statistics about YAML files comparation
--negate | Define mode diff or equal comparation, possible values TRUE/FALSE or 0/1
--limit | Limit results to a specific number
--offset | Starting point of a limit

## Arguments disponibles
Argument | Detalls
---------|-------------
yaml-left | YAML file used as base to compare
yaml-right | YAML file used to find missing parts or differences with the base YAML file
