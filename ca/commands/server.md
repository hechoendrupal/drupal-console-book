# server
Executar el servidor PHP integrat

**Ús:**
```
drupal server [arguments]
serve
rs
```

## Arguments disponibles
Argument | Detalls
---------|-------------
address | Adreça:port valor

## Exemples
* Executar el servidor utilitzant l'argument de l'adreça predeterminat 127.0.0.1:8088
```
drupal server
```
* Enviar l'argument de l'adreça per utilitzar un número de port diferent
```
drupal server 127.0.0.1:8089
```
* S'estan executant els valors de l'argument de l'adreça predeterminada, utilitzeu l'opció --root per definir l'arrel de Drupal
```
drupal --root=/var/www/drupal8.dev server
```
