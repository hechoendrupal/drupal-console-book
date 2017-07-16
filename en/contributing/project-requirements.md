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
mv composer.phar /usr/local/bin/composer
```