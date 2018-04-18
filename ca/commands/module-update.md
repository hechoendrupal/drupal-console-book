# module:update
Update core, module or modules in the application

**Usage:**
```
drupal module:update [arguments] [options]
moup
```

## Available options
Option | Details
-------|-------------
--composer | Update the module using Composer
--simulate | Simulate the update process with Composer

## Available arguments
Argument | Details
---------|-------------
module | Module or modules to be updated should be separated by a space. Leave empty for updating the core and all your modules managed by Composer.

## Examples
* Update module specifying module name and composer parameter
```
drupal module:update  modulename  \
  --composer
```
