# multisite:new
Prepara los archivos para una nueva instalación multisitio.

**Uso:**
```
drupal multisite:new [arguments] [options]
mun
sn
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--copy-default | Copia un sitio existente desde la instalación por defecto.

## Argumentos disponibles
Argumento | Detalles
---------|-------------
directory | Nombre del directorio bajo 'sites' que será creado.
uri | URI del sitio que se añadirá al sites.php.

## Ejemplos
* Configurar los archivos para una instalación por defecto especificando el directorio de destino y la url
```
drupal multisite:new  vendor/newsite http://mysite.example.com
```
