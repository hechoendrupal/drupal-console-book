# Requerimientos del proyecto

## Descargar Git
Recomendamos descargar Git de [http://git-scm.com/downloads](http://git-scm.com/downloads)

## Descargar Composer

Ejecute el siguiente comando desde su terminal para conseguir la última versión de Composer:
```
curl -sS https://getcomposer.org/installer | php
```
O si no tiene curl:
```
php -r "readfile('https://getcomposer.org/installer');" | php
```
Este script es un instalador que simplemente comprobará algunas configuraciones de su php.ini y le advertirá si están establecidas de forma incorrecta. Después descargará el último composer.phar en el directorio actual.

Puede ejecutar este comando en la terminal para hacer Composer fácilmente accesible desde cualquier lugar en su sistema:
```
$ mv composer.phar /usr/local/bin/composer
```

## Descargar Drupal 8
El proyecto Drupal Console sólo soporta Drupal 8; el cual necesitará descargar e instalar localmente.
### Descargar Drupal
```
$ drupal site:new drupal8.dev 8.0.0
$ cd drupal8.dev
```
### Instalar Drupal usando MySQL:
```
$ drupal site:install standard --langcode=en --db-type=mysql --db-host=127.0.0.1 
  --db-name=drupal --db-user=root --db-pass=root --db-port=3306 
  --site-name="Drupal 8 Site Install" --site-mail=admin@example.com 
  --account-name=admin --account-mail=admin@example.com --account-pass=admin -n
```
### Instalar Drupal usando SQLite:
```
$ drupal site:install standard --langcode=en --db-type=sqlite 
  --db-file=sites/default/files/.ht.sqlite --site-name="Drupal 8 Site Install" 
  --site-mail=admin@example.com --account-name=admin --account-mail=admin@example.com
  --account-pass=admin -n
```
### Iniciar el servidor incorporado de PHP
```
$ drupal server
```
**NOTA:** Asegúrese de usar sus propias credenciales de usuario y contraseña cuando ejecute `site:install` y nunca utilice el usuario root en producción. En este código de ejemplo, evitamos todas las preguntas interactivas utilizando el argumento `-n`.
