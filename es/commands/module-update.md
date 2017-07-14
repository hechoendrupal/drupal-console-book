# module:update
Actualizar el core, un módulo o varios en la aplicación

**Usage:**
```
drupal module:update [arguments] [options]
moup
```

## Available options
Option | Details
-------|-------------
--composer | Actualizar el módulo usando Composer
--simulate | Simular el proceso de actualización con Composer

## Available arguments
Argument | Details
---------|-------------
module | El módulo o módulos que vayan a ser actualizados deberían estar separados por un espacio. Déjelo vacío para actualizar el core y todos los módulos gestionados por Composer.

## Examples
* Update module specifying module name and composer parameter
```
drupal module:update  modulename  \
  --composer
```
