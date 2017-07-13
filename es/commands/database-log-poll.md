# database:log:poll
Observar el watchdog e imprimir nuevas entradas en el log cada x segundos

**Uso:**
```
$ drupal database:log:poll [arguments] [options]
$ dblp  
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--type | Filtrar eventos por un tipo específico
--severity | Filtrar eventos por un nivel de severidad específico
--user-id | Filtrar eventos por un id de usuario específico

## Argumentos disponibles
Argumento | Detalles
---------|-------------
duration | Intervalo en segundos para lectura en la base de datos

## Ejemplos
* Print the log entries on screen every x seconds
```
$ drupal database:log:poll \
  100

```
