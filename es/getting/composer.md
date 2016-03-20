# Instala Drupal Console Usando Composer
Puedes instalar este proyecto usando composer.

## Instalando Drupal Console globalmente usando composer:
```
$ composer global require drupal/console:@stable
```

## Agregar el directorio del binario a la ruta de clases:
```
$ echo "PATH=$PATH:~/.composer/vendor/bin" >> ~/.bash_profile
```

## Ahora ejecutar Drupal Console usando:
```
$ drupal generate:module
```
