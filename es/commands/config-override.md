# config:override
Sobreescribir valor de la configuración activa.

**application.gitbook.messages.usage:**
```
drupal config:override [arguments]
co
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
name | Nombre de configuración
key | Clave
value | Valor

## application.gitbook.messages.examples
* Definir el valor de "flood" del módulo Contacto a 10.
```
drupal config:override contact.settings flood.limit 10
```
