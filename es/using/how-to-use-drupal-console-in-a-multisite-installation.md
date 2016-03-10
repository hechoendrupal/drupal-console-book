# Cómo usar Drupal Console en una instalación multisite 
 
Drupal Console proporciona soporte para instalaciones de Drupal multi-site. Este proyecto provee el comando `multisite:debug` para debugear instalaciones multi-site, la opción `--uri` le permite interactuar con este tipo de instalaciones.
 
### Cómo listar todos los multi sitios conocidos
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

### Cómo ejecutar un comando contra una instalación multi-site
```
$ drupal --uri=http://drupal8.multi.dev cr all
```
