# Using the Drupal Console Installer
You can install the Drupal Console locally by running the installer in your project directory, the installer will take care of downloading the necesary files to run drupal console on you computer.

## Using curl:
```
$ curl -LSs http://drupalconsole.com/installer | php
```
## Or if you don't have curl:
```
$ php -r "readfile('http://drupalconsole.com/installer');" | php
```

The installer script will simply check some php.ini settings, warn you if they are set incorrectly, and then download the latest console.phar in the current directory.


## You can now execute console using:
```
$ php console.phar generate:module
```

You can place this file anywhere you wish. If you put it in your PATH, you can access it globally. On unixy systems you can even make it executable and invoke it without php.

### Access console from anywhere on your system
```
$ mv console.phar /usr/local/bin/drupal
```

#### You can now execute console using:
```
$ drupal generate:module
```

**NOTE:** The name `drupal` is just an alias you can name it anything you like.
