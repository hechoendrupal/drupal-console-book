# Install Drupal Console Using Composer
You can install this project using composer.

## Install Drupal Console globally using composer:
```
$ composer global require drupal/console:@stable
```

## Add the binary directory to your class path:
**NOTE:** A common alternative path in the Linux world is `~/.config/composer/vendor/bin` check before adding the new path!
```
$ echo "PATH=$PATH:~/.composer/vendor/bin" >> ~/.bash_profile
```

## You can now execute console using:
```
$ drupal generate:module
```
