# Project requirements

## Download Git
We recommend downloading Git from [http://git-scm.com/downloads](http://git-scm.com/downloads)

## Download Composer

Run this in your terminal to get the latest Composer version:
```
curl -sS https://getcomposer.org/installer | php
```
Or if you don't have curl:
```
php -r "readfile('https://getcomposer.org/installer');" | php
```
This installer script will simply check some php.ini settings, warn you if they are set incorrectly, and then download the latest composer.phar in the current directory

You can run this terminal command to make Composer easily accessible, from anywhere on your system:
```
$ mv composer.phar /usr/local/bin/composer
```

## Download Drupal 8
The Drupal Console project only supports Drupal 8; which you will need to download and install locally.
### Download Drupal
```
$ drupal site:new drupal8.dev 8.0.0
$ cd drupal8.dev
```
### Install Drupal using MySQL:
```
$ drupal site:install standard --langcode=en --db-type=mysql --db-host=127.0.0.1 
  --db-name=drupal --db-user=root --db-pass=root --db-port=3306 
  --site-name="Drupal 8 Site Install" --site-mail=admin@example.com 
  --account-name=admin --account-mail=admin@example.com --account-pass=admin -n
```
### Install Drupal using SQLite:
```
$ drupal site:install standard --langcode=en --db-type=sqlite 
  --db-file=sites/default/files/.ht.sqlite --site-name="Drupal 8 Site Install" 
  --site-mail=admin@example.com --account-name=admin --account-mail=admin@example.com
  --account-pass=admin -n
```
### Start the PHP's built in server
```
$ drupal server
```
**NOTE:** Make sure you use your own user and database credentials when running `site:install` and never user root on production. In this example code, we accept all interactive questions, i.e. answering *“yes”* when passing the `-y` argument.
