# Installing Drupal Console on Windows
On Windows there are two ways to install drupal console. One uses Git Bash, the other uses a Windows command prompt. I recommend using the Git Bash utility from the Git for Windows (previously msysgit) program package, since this is the only way you can use drupal console without prefixing it with php.

## Using curl from the Git Bash prompt:
```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
```
## OR run the following from a Windows command prompt:
```
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar
```

You can now execute it, supposing php.exe is in your PATH environment variable.

## Run:

```
$ php drupal.phar
```

If you rename the drupal.phar file to drupal, and copy it next to php.exe, then from the Git Bash window you can run it without prefixing with php.

#### You can now execute using:
```
$ drupal
```

**NOTE:** The name `drupal` is just an alias you can name it anything you like.
