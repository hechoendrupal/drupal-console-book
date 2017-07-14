# module:download
Скачать модуль или модули в приложение

**Usage:**
```
drupal module:download [arguments] [options]
mod
md
```

## Available options
Option | Details
-------|-------------
--path | The path of the contrib project
--latest | По умолчанию загружать самую последнюю версию
--composer | Download the module using Composer
--unstable | commands.module.install.options.unstable

## Available arguments
Argument | Details
---------|-------------
module | Модуль или модули, которые будут включены должны быть разделены пробелом

## Examples
* Download module specifying module name and its path
```
drupal module:download  modulename  \
  --path="modules/contrib"
```
