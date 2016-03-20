# ¿Cómo usar Drupal Console en una instalación de un sitio remoto?

Drupal Console le permite ejecutar comandos en su servidor local. Además es posible ejecutar comandos en un servidor remoto.

Para utilizar esta característica, utilice la opción `--target` pasándole el nombre del sitio remoto con el que quiere interactuar.  
```
$ drupal --target=sample.dev cr all
```

Configurar su ordenador local para utilizar un sitio remoto requiere un poco de configuración.

### Editar la configuración global
Puede proporcionar una configuración global de las conexiones remotas en el archivo copiado `~/.console/config.yml`. Esta información está agrupada dentro de la clave `remote`.
```
application:
  ...
  remote:
    user: root
    port: 22
    console: /usr/local/bin/drupal
    options:
    arguments:
    keys:
      public: ~/.ssh/id_rsa.pub
      private: ~/.ssh/id_rsa
      passphrase: ~/.ssh/passphrase.txt
```

### Editar la configuración de un sitio específico
Puede proporcionar una configuración de un sitio específico duplicando el archivo `~/.console/sites/sample.yml` y guardándolo con un nuevo nombre en `~/.console/sites/`.

```
local:
  root: /var/www/drupal8.dev
  host: local
dev:
  root: /var/www/html/drupal
  host: 140.211.10.62
  user: drupal
prod:
  root: /var/www/html/docroot
  host: live.drupal.org
  user: drupal
  console: /var/www/html/docroot/console.phar
```

### Depurar sitios
Puede listar todos los sitios locales y remotos ejecutando el comando `site:debug`.
```
$ drupal site:debug

+--------------------+-----------------+------------------------+
| Site               | Host            | Root                   |
+--------------------+-----------------+------------------------+
| sample.local       | local           | /var/www/drupal8.dev   |
| sample.dev         | 140.211.10.62   | /var/www/html/drupal   |
| sample.prod        | live.drupal.org | /var/www/html/docroot  |
+--------------------+-----------------+------------------------+
```

Puede mostrar los detalles de la configuración del sitio pasándo el nombre del sitio como argumento al comando `site:debug`. 
```
$ drupal site:debug sample.dev

user: drupal
port: 22
console: /usr/local/bin/drupal
options:
arguments: 
keys:
    public: ~/.ssh/id_rsa.pub
    private: ~/.ssh/id_rsa
    passphrase: ~/.ssh/passphrase.txt
root: /var/www/html/drupal
host: 140.211.10.62
remote: true
```

**NOTA:** Como ha podido observar la configuración global y la específica de un sitio aparecen juntas al depurar los sitios. Puede sobreescribir cualquier configuración global añadiendo esas claves en la configuración específica del sitio.
