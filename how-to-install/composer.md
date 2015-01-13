# Composer installation
```
$ composer global require drupal/console:@stable
```
You need add the ~/.composer/vendor/bin directory into your class path,
```
$ echo "PATH=$PATH:~/.composer/vendor/bin" > ~/.bashrc
$ console
```