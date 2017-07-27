# module:uninstall
Desinstala un módulo o varios en la aplicación

**Uso:**
```
drupal module:uninstall [arguments] [options]
mou
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--force | ¿ Desea ignorar las dependencias y desinstalar el módulo a la fuerza ?
--composer | Desinstala el módulo mediante Composer

## Argumentos disponibles
Argumento | Detalles
---------|-------------
module | Introduzca el nombre del módulo a desinstalar (pulse <return> para detener esta pregunta)

## Ejemplos
* Desinstalar un módulo especificando el nombre del módulo
```
drupal module:uninstall  modulename
```
