# Connecting to a virtual environment

You can connect to a virtual-machine/docker by providing the proper values for `extra-options` and `type`.

## DrupalVM Example
```
dev:
  root: /var/www/drupalvm/drupal
  host: 192.168.88.88
  user: vagrant
  extra-options: '-o PasswordAuthentication=no -i ~/.vagrant.d/insecure_private_key'
  type: ssh
```

##  Drupal4Docker example
```
dev:
  root: /var/www/html
  extra-options: docker-compose exec --user=82 php
  type: container
```
When connecting using `type: container` there is no need to provide `host` and `user` values.
 