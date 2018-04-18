# module:update
Update core, module or modules in the application

**Utilização:**
```
drupal module:update [arguments] [options]
moup
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--composer | Update the module using Composer
--simulate | Simulate the update process with Composer

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
module | Module or modules to be updated should be separated by a space. Leave empty for updating the core and all your modules managed by Composer.

## Exemplos
* Update module specifying module name and composer parameter
```
drupal module:update  modulename  \
  --composer
```
