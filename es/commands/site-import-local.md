# site:import:local
Importar o configurar un proyecto Drupal existente en local

**Uso:**
```
drupal site:import:local [arguments] [options]
sil
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--environment | Nombre del entorno que va a ser importado

## Argumentos disponibles
Argumento | Detalles
---------|-------------
name | Nombre que se usará para generar la configuración del sitio
directory | Directorio raíz del Drupal existente

## Ejemplos
* Importar un proyecto Drupal local especificando el nombre del sitio y la ruta
```
drupal site:import:local  SiteName /private/var/www/vhost/anexusit/drupal8.dev/web
```
