# yaml:diff
The **yaml:diff** command Compare two YAML files in order to find differences between them.

**Usage:**
```
$ drupal yaml:diff [arguments] [options] 
$ yd  
```

## Available options
Option | Details
-------|-------------
--stats | Print statistics about YAML files comparation
--negate | Define mode diff or equal comparation, possible values TRUE/FALSE or 0/1
--limit | Limit results to a specific number
--offset | Starting point of a limit

## Available arguments
Argument | Details
---------|-------------
yaml-left | YAML file used as base to compare
yaml-right | YAML file used to find missing parts or differences with the base YAML file
