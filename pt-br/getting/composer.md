# Instalar Drupal Console usando Composer
Você pode instalar esse projeto usando composer.

## Instalar Drupal Console globalmente usando composer:
```
$ composer global require drupal/console:@stable
```

## Adicione o diretório binário ao caminho da sua classe:
```
$ echo "PATH=$PATH:~/.composer/vendor/bin" >> ~/.bash_profile
```

## Você agora pode executar o console usando:
```
$ console generate:module
```
