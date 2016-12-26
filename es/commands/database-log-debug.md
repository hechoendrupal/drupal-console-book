# database:log:debug
Desplegar eventos registrados al momento para la aplicación

**Uso:**
```
$ drupal database:log:debug [arguments] [options]
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--type | Filtrar eventos por un tipo específico
--severity | Filtrar eventos por un nivel de severidad específico
--user-id | Filtrar eventos por un id de usuario específico
--asc | Listar eventos en orden ascendiente
--limit | Limitar los resultados a un número específico
--offset | Punto inicial de un límite
--yml | Imprimir en formato YAML

## Argumentos disponibles
Argumento | Detalles
---------|-------------
event-id | ID del evento DBLog
