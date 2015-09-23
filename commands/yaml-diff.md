# yaml:diff
The **yaml:diff** command Compare two YAML files do determined differences between them

**Usage:**
```
$ drupal yaml:diff [arguments] [options] 
```

## Available options
Option | Details
-------|-------------
--negate | Define mode diff or equal comparation, possible values TRUE/FALSE or 0/1
--limit | Limit results to a specific number
--offset | Starting point of a limit

## Available arguments
Argument | Details
---------|-------------
yaml-left | YAML file used as base to compare
yaml-right | YAML file used to determine missing or differences with base YAML file
