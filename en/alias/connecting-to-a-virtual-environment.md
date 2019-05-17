# Connecting to a virtual environment

You can connect to a virtual-machine/docker by providing the proper values for `extra-options` and `type`.

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
By default, the `uri` option is `default` and the `drupal-console-binary` option is `drupal` so it is not necessary to add options, but If you have changed the name of your `drupal-console-binary` or `uri`, You can define the name in the config.

In `extra-options` you can define tty's option if it is necessary, example: `extra-options: '-tt'`

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
 