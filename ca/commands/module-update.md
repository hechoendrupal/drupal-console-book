# module:update
Update core, module or modules in the application

**Ús:**
```
drupal module:update [arguments] [options]
moup
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--composer | Update the module using Composer
--simulate | Simulate the update process with Composer

## Arguments disponibles
Argument | Detalls
---------|-------------
module | Module or modules to be updated should be separated by a space. Leave empty for updating the core and all your modules managed by Composer.

## Exemples
* Update module specifying module name and composer parameter
```
drupal module:update  modulename  \
  --composer
```
