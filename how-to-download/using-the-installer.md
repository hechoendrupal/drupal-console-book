# Using the Installer

Installing Console locally is a matter of just running the installer in your project directory:

```
$ curl -LSs http://drupalconsole.com/installer | php
```
Or if you don't have curl:
```
$ php -r "readfile('http://drupalconsole.com/installer');" | php
```

This installer script will simply check some php.ini settings, warn you if they are set incorrectly, and then download the latest console.phar in the current directory. 

You can now execute console using:
```
$ php console.phar generate:module
```

You can place this file anywhere you wish. If you put it in your PATH, you can access it globally. On unixy systems you can even make it executable and invoke it without php.

You can run these commands to easily access composer from anywhere on your system:
```
$ mv console.phar /usr/local/bin/drupal
```

You can now execute console using:

```
$ drupal generate:module
```
