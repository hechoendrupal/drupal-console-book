# module:uninstall
Uninstall module or modules in the application

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
module | Module name (press <return> to stop adding modules)

## Examples
* Uninstall the module specifying the module name
```
drupal module:uninstall  modulename
```
