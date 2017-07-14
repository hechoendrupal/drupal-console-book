# module:download
Download module or modules in application

**Usage:**
```
drupal module:download [arguments] [options]
mod
```

## Available options
Option | Details
-------|-------------
--path | The path of the contrib project
--latest | Default to download most recent version
--composer | Download the module using Composer
--unstable | commands.module.install.options.unstable

## Available arguments
Argument | Details
---------|-------------
module | Module or modules to be enabled should be separated by a space

## Examples
* Download module specifying module name and its path
```
drupal module:download  modulename  \
  --path="modules/contrib"
```
