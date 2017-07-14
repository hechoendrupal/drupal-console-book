# module:download
Descarga un módulo o varios en la aplicación

**Usage:**
```
drupal module:download [arguments] [options]
mod
md
```

## Available options
Option | Details
-------|-------------
--path | La ruta de contrib del proyecto
--latest | Valor por defecto que descarga la versión más reciente
--composer | Descarga el módulo usando Composer
--unstable | commands.module.install.options.unstable

## Available arguments
Argument | Details
---------|-------------
module | El módulo o los módulos que vayan a ser habilitados deben ir separados por un espacio

## Examples
* Download module specifying module name and its path
```
drupal module:download  modulename  \
  --path="modules/contrib"
```
