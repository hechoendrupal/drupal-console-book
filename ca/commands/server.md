# server
El comandament **server** executa Executar servidor PHP integrat

**Ús:**
```
$ drupal server [arguments] 
```

## Arguments disponibles
Argument | Detalls
---------|-------------
address | L'adreça:port value

## Exemples
* Executar utilitzant l'argument de l'adreça predeterminat 127.0.0.1.8088
```
$ drupal server
```
* Enviar l'argument de l'adreça per utilitzar un número de port diferent
```
$ drupal server 127.0.0.1:8089
```
* Executant l'argument de l'adreça predeterminat, utilitzant l'opció --root per definir l'arrel de Drupal
```
$ drupal --root=/var/www/drupal8.dev server
```
