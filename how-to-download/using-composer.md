# Using Composer

You can use composer to install console globally using the folowing command:

```
$ composer global require drupal/console:@stable
```

After that you will need add the ~/.composer/vendor/bin directory into your class path,
```
$ echo "PATH=$PATH:~/.composer/vendor/bin" > ~/.bashrc
```

You can now execute console using: 
```
$ console generate:module
```