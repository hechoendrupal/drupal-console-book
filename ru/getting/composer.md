# Установка с помощью приложения Composer

Перейти в папку с Drupal:

```
cd /path/to/drupal8.dev
```

Установка командой composer require: 

```
composer require drupal/console:~1.0 \
--prefer-dist \
--optimize-autoloader
```

## Скачать шаблон DrupalComposer

```
composer create-project \
drupal-composer/drupal-project:8.x-dev \
drupal8.dev \
--prefer-dist \
--no-progress \
--no-interaction
```

## Обновить Drupal Console:

```
composer update drupal/console --with-dependencies
```
