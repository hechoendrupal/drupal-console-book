# config:override
Sobreescribir valor de la configuración activa.

**Uso:**
```
drupal config:override [arguments]
co
```

## Argumentos disponibles
Argumento | Detalles
---------|-------------
name | Nombre de configuración
key | Clave
value | Valor

## Ejemplos
* Definir el valor de "flood" del módulo Contacto a 10.
```
drupal config:override contact.settings flood.limit 10
```
