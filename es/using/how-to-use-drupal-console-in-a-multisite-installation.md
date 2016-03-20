# ¿Cómo usar Drupal Console en una instalación multisitio?
 
Drupal Console proporciona soporte para instalaciones de Drupal multisitio. El proyecto provee el comando `multisite:debug` para depurar instalaciones multisitio y la opción `--uri` que permite interactuar con este tipo de instalaciones.
 
### ¿Cómo listar todos los multisitios conocidos?
```
$ drupal multisite:debug

+---------------------+--------------------------------+
| Sitio               | Directorio                     |
+---------------------+--------------------------------+
| drupal8.dev         | /var/www/drupal8.dev/default   |
| drupal8.multi.dev   | /var/www/drupal8.dev/multi.dev |
+---------------------+--------------------------------+

 Los Sitios son listados con el formato: <port>.<domain>.<path>
```

### ¿Cómo ejecutar un comando que forma parte de una instalación multisitio?
```
$ drupal --uri=http://drupal8.multi.dev cr all
```
