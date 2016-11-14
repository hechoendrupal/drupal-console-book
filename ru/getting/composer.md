# Установка с помощью Composer

Чтобы установить Drupal Console при помощи приложения `composer`, нужно выполнить следующие команды.

## Установить Drupal Console глобано используя composer:
```
$ composer global require drupal/console:@stable
```

## Добавить директорию с приложением в переменную `PATH` операционной системы:
```
$ echo "PATH=$PATH:~/.composer/vendor/bin" >> ~/.bash_profile
```

## Запустить Drupal Console:
```
$ drupal generate:module
```
