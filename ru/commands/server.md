# server
The **server** command Runs PHP built-in web server

**Использование:**
```
$ drupal server [arguments] 
```

## Доступные параметры
Параметр | Описание
---------|-------------
address | The address:port values

## Examples
* Run using default address argument value 127.0.0.1.8088
```
$ drupal server
```
* Passing address argument to use a different port number
```
$ drupal server 127.0.0.1:8089
```
* Running default address argument values, using --root option to define the Drupal root
```
$ drupal --root=/var/www/drupal8.dev server
```
