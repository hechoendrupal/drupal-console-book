# debug:database:log
Muestra los eventos de log actuales de la aplicación

**Uso:**
```
drupal debug:database:log [arguments] [options]
dbb
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
event-id | ID de evento de DBLog

## Ejemplos
* Listar todas las entradas del log
```
drupal debug:database:log
```
* Listar una entrada del log específica por ID de evento
```
drupal debug:database:log 21228
```
