# Install Drupal Console Using Composer
You can install this project using composer.

## Install Drupal Console globally using composer:
```
$ composer global require drupal/console:@stable
```

## Add the binary directory to your class path:
```
$ echo "PATH=$PATH:~/.composer/vendor/bin" >> ~/.bash_profile
```

## You can now execute console using:
```
$ drupal generate:module
```
