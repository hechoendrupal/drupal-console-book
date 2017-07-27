# module:install
Instala un módulo o varios en la aplicación

**Uso:**
```
drupal module:install [arguments] [options]
moi
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--latest | Por defecto descarga la versión más reciente
--composer | Desinstala el módulo mediante Composer

## Argumentos disponibles
Argumento | Detalles
---------|-------------
module | El módulo o los módulos que vayan a ser habilitados deben ir separados por un espacio

## Ejemplos
* Instalar un módulo especificando el nombre del módulo
```
drupal module:install  modulename
```
