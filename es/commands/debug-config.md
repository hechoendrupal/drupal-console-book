# debug:config
Lista los nombres de objetos de configuración y objectos de configuración única.

**Uso:**
```
drupal debug:config [arguments] [options]
dc
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--show-overridden | Mostrar configuraciones sobreescritas.

## Argumentos disponibles
Argumento | Detalles
---------|-------------
name | Nombre de configuración de objeto, por ejemplo "system.site".

## Ejemplos
* Lista todos los nombres de objeto de configuración.
```
drupal config:debug
```
* Muestra los valores de configuración de sistema del sitio.
```
drupal config:debug system.site
```
* Lista todos los nombres de configuración de sistema.
```
drupal config:debug | grep system
```
* Lista toda la configuración incluyendo los valores sobreescritos.
```
drupal debug:config --show-overridden
```
