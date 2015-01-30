# Using Composer

You can use composer to install console globally using the following command:

```
$ composer global require drupal/console:@stable
```

Add the binary directory to your class path:
```
$ echo "PATH=$PATH:~/.composer/vendor/bin" > ~/.bash_profile
```

You can now execute console using: 
```
$ console generate:module
```