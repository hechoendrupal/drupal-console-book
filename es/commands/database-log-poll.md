# database:log:poll
Editar en vivo el watchdog imprimiendo las nuevas entradas en el log cada x segundos

**Uso:**
```
drupal database:log:poll [arguments] [options]
dblp
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
duration | Duración en segundos en los que se producirá el intervalo de lecturas en la base de datos

## Ejemplos
* Imprimir las entradas del log cada x segundos
```
drupal database:log:poll \
  100
```
