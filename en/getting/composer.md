# Install Drupal Console Using Composer

Change directory to Drupal site:
```
cd /path/to/drupal8.dev
```

Execute composer require command: 
```
composer require drupal/console:~1.0 \
--prefer-dist \
--optimize-autoloader
```

If you install Drupal Console Using Composer on Docksal, execute following command firstly:

```
fin exec git config --global core.filemode false
```

## Download using DrupalComposer project template
```
composer create-project \
drupal-composer/drupal-project:8.x-dev \
drupal8.dev \
--prefer-dist \
--no-progress \
--no-interaction
```

## Update DrupalConsole
```
composer update drupal/console --with-dependencies
```
