# Conectando a un entorno virtual

Puede conectar a una máquina virtual o docker facilitando los valores adecuados para `extra-options` y `type`.

## Pantheon Example
```
dev:
  root: /path/to/pantheon/drupal
  host: pantheonHost
  user: pantheonUsername
  type: ssh
  options:
    uri: default
    drupal-console-binary: drupal
  extra-options: '-o "AddressFamily inet"'  
```
Por defecto, la opción `uri` es` default` y la opción `drupal-console-binary` es` drupal`, por lo que no es necesario agregar opciones, pero si ha cambiado el nombre de su consola binaria drupal o uri, puede definir el nombre en la configuración.

En `extra-options` puedes definir la opción de tty si es necesario, ejemplo:` extra-options: '-tt'`


## Ejemplo DrupalVM
```
dev:
  root: /var/www/drupalvm/drupal
  host: 192.168.88.88
  user: vagrant
  extra-options: '-o PasswordAuthentication=no -i ~/.vagrant.d/insecure_private_key'
  type: ssh
```

##  Ejemplo Drupal4Docker
```
dev:
  root: /var/www/html
  extra-options: docker-compose exec --user=82 php
  type: container
```
Si realiza la conexión usando `type: container` no es necesario facilitar un valor ni para `host` ni para `user`.
