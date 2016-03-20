# Usando el instalador de Drupal Console
Puede instalar localmente Drupal Console ejecutando el instalador en el directorio de su proyecto. El instalador se ocupará de descargar los archivos necesarios para ejecutar Drupal Console en su computadora.

## Usando curl:
```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
```
## O si no tiene curl instalado:
```
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar
```

## Ahora puede ejecutar Drupal Console con:
```
$ php drupal.phar
```

Puede colocar este archivo phar en cualquier lugar que desee. Si lo pone en su $PATH, podrá acceder a él globalmente. En sistemas unix, incluso puede hacerlo ejecutable e invocarlo sin php.

### Acceso desde cualquier directorio en su computadora
```
$ mv drupal.phar /usr/local/bin/drupal
```

### Aplique permisos de ejecutable al archivo descargado:
```
$ chmod +x /usr/local/bin/drupal
```

#### Ahora puede ejecutarlo simplemente escribiendo:
```
$ drupal
```

**NOTA:** El nombre `drupal` es sólo un alias. Puede utilizar el nombre que prefiera.
