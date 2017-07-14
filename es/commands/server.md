# server
Lanza el servidor web PHP interno

**application.gitbook.messages.usage:**
```
drupal server [arguments]
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
address | Los valores dirección:puerto

## application.gitbook.messages.examples
* Corre usando el valor de dirección por defecto 127.0.0.1:8088
```
drupal server
```
* Pasar una dirección para usar un número de puerto diferente
```
drupal server 127.0.0.1:8089
```
* Ejecutando la dirección por defecto, usando la opción --root para indicar la ruta raíz de Drupal
```
drupal --root=/var/www/drupal8.dev server
```
