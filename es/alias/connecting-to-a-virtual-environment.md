# Conectando a un entorno virtual

Puede conectar a una máquina virtual o docker facilitando los valores adecuados para `extra-options` y `type`.

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
