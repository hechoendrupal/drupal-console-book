# debug:database:log
Desplegar eventos registrados al momento para la aplicación

**application.gitbook.messages.usage:**
```
drupal debug:database:log [arguments] [options]
dbb
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--type | Filtrar eventos por un tipo específico
--severity | Filtrar eventos por un nivel de severidad específico
--user-id | Filtrar eventos por un id de usuario específico
--asc | Listar eventos en orden ascendiente
--limit | Limitar los resultados a un número específico
--offset | Punto inicial de un límite
--yml | Imprimir en formato YAML

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
event-id | ID del evento DBLog
