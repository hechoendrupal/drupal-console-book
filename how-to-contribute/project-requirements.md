# Project requirements

* [Git](http://git-scm.com/)
* [Composer](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx)
* [Box](http://box-project.org/)
* [Drupal 8](https://www.drupal.org/project/drupal/git-instructions)

### Download git
We recomend you download git from [http://git-scm.com/downloads](http://git-scm.com/downloads)

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

### Download box
The console project requires [Box](http://box-project.org/) project to create the console.phar. Box is an application that simplifies the Phar building process. Install in your system executing the following command.

```
curl -LSs https://box-project.github.io/box2/installer.php | php
```

You can run this command to easily access box from anywhere on your system:

```
$ mv box.phar /usr/local/bin/box
```

### Download Drupal 8
The console project only support Drupal 8, you need to download and install it locally.
```
$ git clone --branch 8.x http://git.drupal.org/project/drupal.git drupal8.dev
$ cd drupal8.dev
```
You can install Drupal through the UI or using drush:
```bash
$ drush si standard --db-url=mysql://roo:root@localhost/drupal 
  --site-name=drupal8.dev --account-name=admin --account-pass=admin 
  --account-mail=[user-email] -y
```

**NOTE:** Make sure you use your own user and database credentials when running drush si and never user root on production. In this example code we are accepting any interaction answering yes when passing the `-y` argument.