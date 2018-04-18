# site:import:local
Importar/Configurar um projeto local existente do Drupal

**Utilização:**
```
drupal site:import:local [arguments] [options]
sil
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--environment | Nome do ambiente que será importado

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
name | Nome que será usado para gerar a configuração do site
directory | Diretório raíz do Drupal existente

## Exemplos
* Import local drupal project specifying the site name and the path
```
drupal site:import:local  SiteName /private/var/www/vhost/anexusit/drupal8.dev/web
```
