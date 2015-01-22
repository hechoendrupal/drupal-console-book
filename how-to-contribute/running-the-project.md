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

#### Create a custom Phar

To create a Phar file base in our dev version execute the following command

```
$ cd /path/to/DrupalAppConsole
$ box build
```

As result you will the a new file **console.phar**

**NOTE:** Make sure you set `phar.readonly` to '0' in your [php.ini](http://php.net/manual/en/phar.configuration.php)
