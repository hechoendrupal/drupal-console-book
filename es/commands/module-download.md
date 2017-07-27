# module:download
Descarga un módulo o varios en la aplicación

**Uso:**
```
drupal module:download [arguments] [options]
mod
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--path | La ruta de contrib del proyecto
--latest | Valor por defecto que descarga la versión más reciente
--composer | Descarga el módulo usando Composer
--unstable | commands.module.install.options.unstable

## Argumentos disponibles
Argumento | Detalles
---------|-------------
module | El módulo o los módulos que vayan a ser habilitados deben ir separados por un espacio

## Ejemplos
* Descargar un módulo indicando el nombre del módulo y su ruta
```
drupal module:download  modulename  \
  --path="modules/contrib"
```
