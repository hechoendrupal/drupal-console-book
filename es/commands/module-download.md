# module:download
Descarga un módulo o varios en la aplicación

**application.gitbook.messages.usage:**
```
drupal module:download [arguments] [options]
mod
md
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--path | La ruta de contrib del proyecto
--latest | Valor por defecto que descarga la versión más reciente
--composer | Descarga el módulo usando Composer
--unstable | commands.module.install.options.unstable

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
module | El módulo o los módulos que vayan a ser habilitados deben ir separados por un espacio
