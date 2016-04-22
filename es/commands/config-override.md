# config:override
Sobreescribir valor de la configuración activa.

**Uso:**
```
$ drupal config:override [arguments]
```

## Argumentos disponibles
Argumento | Detalles
---------|-------------
config-name | Nombre de la configuración.
key | Clave
value | Valor

## Ejemplos
* Definir el valor de "flood" del módulo Contacto a 10.
```
$ drupal config:override contact.settings flood.limit 10
```
