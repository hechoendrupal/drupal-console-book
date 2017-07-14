# site:import:local
Importar/Configurar um projeto local existente do Drupal

**Usage:**
```
drupal site:import:local [arguments] [options]
sil
```

## Available options
Option | Details
-------|-------------
--environment | Nome do ambiente que será importado

## Available arguments
Argument | Details
---------|-------------
name | Nome que será usado para gerar a configuração do site
directory | Diretório raíz do Drupal existente

## Examples
* Import local drupal project specifying the site name and the path
```
drupal site:import:local  SiteName /private/var/www/vhost/anexusit/drupal8.dev/web
```
