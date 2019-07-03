# Instalar Drupal Console usando Composer en un proyecto existente

Cambie el directorio al sitio de Drupal:
```
cd /path/to/drupal8.dev
```

Ejecutar el comando del compositor requiere:
```
composer require drupal/console:~1.0 \
--prefer-dist \
--optimize-autoloader
```

Si instala Drupal Console usando Composer en Docksal, primero ejecute el siguiente comando:
```
fin exec git config --global core.filemode false
```

## Descargar usando la plantilla de proyecto DrupalComposer
Esta opción descarga un nuevo proyecto de drupal con drupalConsole incluido.
```
composer create-project \
drupal-composer/drupal-project:8.x-dev \
drupal8.dev \
--prefer-dist \
--no-progress \
--no-interaction
```

## Actualizar DrupalConsole
```
composer update drupal/console --with-dependencies
```
