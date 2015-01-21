# Getting Started

### Requirements
* [Composer](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx)
* Set phar.readonly to '0' in your [php.ini](http://php.net/manual/en/phar.configuration.php)
* [Box](http://box-project.org/)
* Git

### Install
First, clone the project from the git repository and install all the dependecies with composer
```bash
$ git clone git@github.com:hechoendrupal/DrupalAppConsole.git
$ cd DrupalAppConsole
composer install --no-dev
```

### Runnig the console
The console commands run only with a Drupal 8 installation, so you need to download and install it
```bash
$ cd ../
$ git clone --branch 8.x http://git.drupal.org/project/drupal.git drupal8
$ cd drupal8
```
You can install Drupal through the UI or with drush
```bash
$ drush si standard --db-url=mysql://drupal:drupal@localhost/drupal --site-name=drupal8.dev --account-name=admin --account-pass=admin --account-mail=[user-email]
```
By this time we should have 2 folder, one with Console and other with Drupal 8. Something like this
```
|- drupal8
|- DrupalAppConsole
```
To sync the console with the drupal installacion, You just need to create an Symbolic link inside your drupal installation
```bash
ln -s ../DrupalAppConsole/bin/console console
```
Now just type `php console` and it should show you the list of available commands

### Creating the console.phar
The console use the [Box](http://box-project.org/) project to create the console.phar. To create it first download the box.phar file inside the console project
```bash
curl -LSs https://box-project.github.io/box2/installer.php | php
```
Then just run `php box.phar build -v` to create the console.phar. Make sure you set the `phar.read_only = 0` in your php.ini
