# Using Composer

You can use composer to install console globally using the folowing command:

```
$ composer global require drupal/console:@stable
```

Add the binary directory `~/.composer/vendor/bin` to your class path
```
$ echo "PATH=$PATH:~/.composer/vendor/bin" > ~/.bashrc
```

You can now execute console using: 
```
$ console generate:module
```