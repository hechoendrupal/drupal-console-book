# Configurando su máquina local

Para usar un alias de sitio se requiere algo de configuración local.

## Configuración global

La configuración global puede ser establecida usando el archivo copiado file `~/.console/config.yml`. Esta información está agrupada dentro de la clave `remote`.

```
application:
  ...
  remote:
    user: drupal
    port: 22
    options:
    arguments:
    type: ssh
```

## Configuración específica de un sitio

La configuración de alias de sitio puede ser establacida añadiendo un archivo YAML en `/path/to/site/console/sites/sample.yml` o `~/.console/sites/sample.yml`

```
local:
  root: /var/www/drupal8.dev
  type: local
dev:
  root: /var/www/html/drupal
  host: 140.211.10.62
  user: drupal
  type: ssh
prod:
  root: /var/www/html/docroot
  host: live.drupal.org
  user: drupal
  type: ssh
```

## Debugueando mis sitios.

Todos los alias de sitios conocidos pueden ser listados ejecutando el comando `debug:site`.

```
drupal debug:site

+--------------------+-----------------+------------------------+
| Site               | Host            | Root                   |
+--------------------+-----------------+------------------------+
| sample.local       | local           | /var/www/drupal8.dev   |
| sample.dev         | 140.211.10.62   | /var/www/html/drupal   |
| sample.prod        | live.drupal.org | /var/www/html/docroot  |
+--------------------+-----------------+------------------------+
```

Los detalles de una configuración de sitio pueden ser mostrados pasando el nombre del sitio como argumento al comando `debug:site`.
```
drupal debug:site sample.dev

user: drupal
port: 22
options:
arguments:
root: /var/www/html/drupal
host: 140.211.10.62
type: ssh
```

**NOTA:** Como ha podido observar, la configuración global y la de un sitio específico se mergean cuando se debuguea un sitio. Puede sobreescribir cualquier configuración global añadiendo esas claves en la configuración específica de cada sitio.
