# Usando el instalador de Drupal Console
Puede instalar localmente Drupal Console lanzando el instalador en el directorio de su proyecto, el instalador se ocupará de descargar los archivos necesarios para ejecutar Drupal Console en su ordenador.

## Usando curl:
```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
```
## O si no dispone de curl:
```
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar
```

## Ahora puede ejecutar Drupal Console ejecutando:
```
$ php drupal.phar
```

Puede colocar este archivo phar en cualquier lugar que desee. Si lo pone en su PATH, podrá acceder a él globalmente. En sistemas unix,  incluso puede hacerlo ejecutable e invocarlo sin php.

### Acceso desde cualquier lugar de su máquina
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

**NOTA:** El nombre `drupal` es sólo un alias que puede llamar de cualquier modo que desee.
