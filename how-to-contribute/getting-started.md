### Requirements
* [Git](http://git-scm.com/)
* [Composer](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx)
* [Box](http://box-project.org/)
* [Drupal 8](https://www.drupal.org/project/drupal/git-instructions)

### Fork
Fork your own copy of [hechoendrupal/DrupalAppConsole](https://github.com/hechoendrupal/DrupalAppConsole/fork) to your account

### Clone
Get a copy of your recently cloned version of console in your machine
```
$ git clone git@github.com:[your-git-user-here]/DrupalAppConsole.git
```

### Install dependencies
Now that you clone the project you need to download depencencies via componser

```
$ composer update --no-dev
```

**NOTE:** Make sure run composer from the directory where the project was cloned.
```
$ cd /path/to/DrupalAppConsole
```

### Download Composer

Run this in your terminal to get the latest Composer version:
```
curl -sS https://getcomposer.org/installer | php
```
Or if you don't have curl:
```
php -r "readfile('https://getcomposer.org/installer');" | php
```
This installer script will simply check some php.ini settings, warn you if they are set incorrectly, and then download the latest composer.phar in the current directory

You can run this commands to easily access composer from anywhere on your system:
```
$ mv composer.phar /usr/local/bin/composer
```