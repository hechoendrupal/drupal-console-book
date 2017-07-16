# Installing Drupal Console on Windows
On Windows there are two ways to install drupal console. One uses Git Bash, the other uses a Windows command prompt. I recommend using the Git Bash utility from the Git for Windows (previously msysgit) program package, since this is the only way you can use drupal console without prefixing it with php.

## Using on Git Bash:

If you use Drupal Console on Git Bash, please install packages below:

* [Git for Windows](https://git-for-windows.github.io/)
* [Composer](https://github.com/composer/windows-setup)
* [PHP For Windows](http://windows.php.net/download/)
* [sqlite-tools-win32-x86](https://www.sqlite.org/download.html)

### Update PATH environment

After installation, you have to include php.exe and sqlite3.exe in your PATH environment variable.
For example, if you extracted "PHP For Windows" into "C:\php", and extracted "sqlite-tools-win32-x86" into "C:\sqlite", you can set PATH environment variable as below from command prompt.

```
SETX /M PATH "%PATH%;C:\php;C:\sqlite"
```

### Setup php.ini

Drupal Console require some extensions. please enable these extensions in your php.ini.

```
extension=php_gd2.dll
extension=php_pdo_sqlite.dll
extension=php_curl.dll
extension=php_openssl.dll
```

We recommend to enable the following extensions to enable you to use your own language.
```
extension=php_intl.dll
extension=php_mbstring.dll
```

#### Define certificate

put certificate information provided by Git for Windows.
```
curl.cainfo = C:\Program Files\Git\usr\ssl\certs\ca-bundle.crt;
```

### Install Drupal Console globally using composer:
```
composer global require drupal/console:~1
```

### You can now execute console using:

```
drupal
```

or execute one of the chain available, to execute a quick install execute the following command

```
drupal chain --file="C:\Users\username\.console\chain\quick-start.yml"
```

**NOTE:** You have to provide "Windows-style" path for `file` option.
