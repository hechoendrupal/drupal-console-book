# module:download
Descarregar mòduls a la aplicació

**Usage:**
```
drupal module:download [arguments] [options]
mod
```

## Available options
Option | Details
-------|-------------
--path | The path of the contrib project
--latest | Descarregar la versió més actual de forma predeterminada
--composer | Download the module using Composer
--unstable | Module unstable

## Available arguments
Argument | Details
---------|-------------
module | Mòduls per habilitar separats per un espai

## Examples
* Download module specifying module name and its path
```
drupal module:download  modulename  \
  --path="modules/contrib"
```
