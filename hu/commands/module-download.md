# module:download
Modul vagy modulok letöltése

**Usage:**
```
drupal module:download [arguments] [options]
mod
```

## Available options
Option | Details
-------|-------------
--path | The path of the contrib project
--latest | Az alapértelmezés a legfrissebb verzió letöltése
--composer | Download the module using Composer
--unstable | Module unstable

## Available arguments
Argument | Details
---------|-------------
module | Az engedélyezendő modulokat szóközzel kell elválasztani

## Examples
* Download module specifying module name and its path
```
drupal module:download  modulename  \
  --path="modules/contrib"
```
