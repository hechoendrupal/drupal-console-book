# site:import:local
Importar o configurar un proyecto Drupal existente en local

**Usage:**
```
drupal site:import:local [arguments] [options]
sil
```

## Available options
Option | Details
-------|-------------
--environment | Nombre del entorno que va a ser importado

## Available arguments
Argument | Details
---------|-------------
name | Nombre que se usará para generar la configuración del sitio
directory | Directorio raíz del Drupal existente

## Examples
* Import local drupal project specifying the site name and the path
```
drupal site:import:local  SiteName /private/var/www/vhost/anexusit/drupal8.dev/web
```
