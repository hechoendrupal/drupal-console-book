# Installing Drupal Console on Windows
On Windows there are two ways to install drupal console. One uses Git Bash, the other uses a Windows command prompt. I recommend using the Git Bash utility from the Git for Windows (previously msysgit) program package, since this is the only way you can use drupal console without prefixing it with php.

## Using on Git Bash:

If you use Drupal Console on Git Bash, please install packages below:

* [Git for Windows](https://git-for-windows.github.io/)
* [Composer](https://github.com/composer/windows-setup)
* [PHP For Windows](http://windows.php.net/download/)
* [sqlite-tools-win32-x86](https://www.sqlite.org/download.html)

After installation, you have to include php.exe and sqlite3.exe in your PATH environment variable.

### Setup php.ini

Drupal Console require some extensions. please enable these extensions in your php.ini.

```
extension=php_gd2.dll
extension=php_pdo_sqlite.dll
```

And we recommend to enable another several extensions to use your local language.
```
extension=php_intl.dll
extension=php_mbstring.dll
```

Finally, put cert information.
```
curl.cainfo = C:\Program Files\Git\usr\ssl\certs\ca-bundle.crt;
```

### Install Drupal Console globally using composer:
```
$ composer global require drupal/console:@stable
```

### You can now execute console using:
```
$ drupal chain --file="C:\Users\username\.console\chain\quick-start.yml"
```

**NOTE:** You have to provide "Windows-style" path for `file` option.
