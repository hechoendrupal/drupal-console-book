# module:uninstall
Desinstala módulos ou módulos na aplicação

**Usage:**
```
drupal module:uninstall [arguments] [options]
mou
```

## Available options
Option | Details
-------|-------------
--force | Quer ignorar as dependências desinstalar o módulo forçadamente?
--composer | Uninstalls the module using Composer

## Available arguments
Argument | Details
---------|-------------
module | Digite o nome do módulo

## Examples
* Uninstall the module specifying the module name
```
drupal module:uninstall  modulename
```
