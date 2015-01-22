# Running the project


After using composer to download dependencies you can run the project executing:

```
$ bin/console
```

### Create a symbolic link

You can run this command to easily access console from anywhere on your system:

```
$ sudo ln -s /path/to/DrupalAppConsole/bin/console /usr/local/bin/console.dev
```

**NOTE:** The name `console.dev` is just an alias you can name it anything you like.


### Download box
The console project requires [Box](http://box-project.org/) project to create the console.phar. Box is an application that simplifies the Phar building process. Install in your system executing the following command.

```
curl -LSs https://box-project.github.io/box2/installer.php | php
```

You can run this command to easily access box from anywhere on your system:

```
$ mv box.phar /usr/local/bin/box
```

#### Create a custom Phar

To create a Phar file base in our dev version execute the following command

```
$ cd /path/to/DrupalAppConsole
$ box build
```

As result you will the a new file **console.phar**

**NOTE:** Make sure you set `phar.readonly` to '0' in your [php.ini](http://php.net/manual/en/phar.configuration.php)

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
