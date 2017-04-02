# Using the Drupal Console Installer
You can install Drupal Console locally by running the installer in your project directory; the installer will take care of downloading the necessary files to run Drupal Console on your computer.

## Using curl:
```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
```
## Or if you don't have curl:
```
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar
```

## You can now execute using:
```
$ php drupal.phar
```

You can place this file anywhere you wish. If you put it in your PATH, you can access it globally. On unixy systems you can even make it executable and invoke it without php.

### Access from anywhere on your system
```
$ mv drupal.phar /usr/local/bin/drupal
```

### Apply executable permissions on the downloaded file:
```
$ chmod +x /usr/local/bin/drupal
```

#### You can now execute using:
```
$ drupal
```
#### Adding to an existing site
You can add Drupal Console at any stage of development of a Drupal 8 site but if you have already installed Drupal and have the site running then, after following the instructions above, you will still need to add the project to your site in addition to being added globally.

The easiest way to do this is using composer from the root of the site:
```
composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```


**NOTE:** The name `drupal` is just an alias you can name it anything you like.
