# Install Drupal Console Using Composer

## Install Drupal Console globally with the following command:
```
$ composer global require drupal/console:@stable
```

## Add the binary directory to your class path:
```
$ echo "PATH=$PATH:~/.composer/vendor/bin" > ~/.bash_profile
```

## You can now execute console using (see [Available commands](../using_drupal_console/available-commands.md)
):
```
$ console generate:module
```
