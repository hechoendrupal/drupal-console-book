# module:uninstall
Dezinstalează un modul sau mai multe din aplicaţie.

**Usage:**
```
drupal module:uninstall [arguments] [options]
mou
```

## Available options
Option | Details
-------|-------------
--force | Do you want to ignore dependencies and forcefully uninstall the module?
--composer | Uninstalls the module using Composer

## Available arguments
Argument | Details
---------|-------------
module | Enter module name

## Examples
* Uninstall the module specifying the module name
```
drupal module:uninstall  modulename
```
