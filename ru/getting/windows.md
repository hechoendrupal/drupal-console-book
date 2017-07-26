# Установка на Windows ОС

Существует два варианта установки Drupal Console на Windows ОС: 
используя приложение Git Bash или используя коммандную строку Windows ОС. 
Мы рекомендуем приложение Git Bash из пакета приложений Git for Windows 
(ранее msysgit), так как это единственный вариант для запуска Drupal Console 
без префикса `php`.

## В окне команадной строки приложения Git Bash:

Для работы с Drupal Console в окне команадной строки приложения Git Bash 
установите следующие приложения:

* [Git для Windows](https://git-for-windows.github.io/)
* [Composer](https://github.com/composer/windows-setup)
* [PHP для Windows](http://windows.php.net/download/)
* [sqlite-tools-win32-x86](https://www.sqlite.org/download.html)

### Обновите переменную `PATH` операционной системы:

Добавьте php.exe и sqlite3.exe в переменную `PATH` операционной системы.
Например, если вы установили "PHP For Windows" в папку "C:\php", 
а приложение "sqlite-tools-win32-x86" в папку "C:\sqlite", 
переменная `PATH` операционной системы может быть обновлена следующим образом
в командной строке:

```
SETX /M PATH "%PATH%;C:\php;C:\sqlite"
```

### Конфигурация php.ini

Drupal Console зависит от следующих PHP-расширений. 
Убедитесь, что они подключены в файле `php.ini`.

```
extension=php_gd2.dll
extension=php_pdo_sqlite.dll
extension=php_curl.dll
extension=php_openssl.dll
```

Мы также рекомендуем подключить PHP-расширения для поддержки языков:

```
extension=php_intl.dll
extension=php_mbstring.dll
```

#### Конфигурация сертификатов

Обновите информацию о сертификатах, предоставленных приложением Git для Windows.

```
curl.cainfo = C:\Program Files\Git\usr\ssl\certs\ca-bundle.crt;
```

### Глобальная установка Drupal Console с помощью приложения composer:

```
composer global require drupal/console:~1
```

### Команда для запуска Drupal Console:

```
$ drupal
```

или запустите одну из цепных (chain) комманд. 
К примеру, для быстой установки Drupal используйте следующую команду

```
$ drupal chain --file="C:\Users\username\.console\chain\quick-start.yml"
```

**ВНИМАНИЕ:** Все пути к папкам для опции `file` должны быть в формате "Windows ОС".
