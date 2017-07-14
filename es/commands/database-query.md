# database:query
Ejecuta una sentencia SQL directamente como argumento

**Usage:**
```
drupal database:query [arguments] [options]
dbq
```

## Available options
Option | Details
-------|-------------
--quick | No cachear cada resultado de query, imprimir cada fila como se recive
--debug | Imprime información de debug, memoria y estaísticas de uso de CPU
--html | Produce un resultado en formato HTML
--xml | Produce un resultado en formato XML
--raw | No se escapan los caracteres especiales en la salida.
--vertical | Imprimir el las filas del resultado de la query verticalmente
--batch | Imprimir los resultados usando el tabulador como separador de columnas, con cada fila en una nueva línea. Con esta opción mysql no usa el archivo de historia

## Available arguments
Argument | Details
---------|-------------
query | La sentencia SQL que será ejecutada
database | Base de datos en el settings.php

## Examples
* Send a database query
```
drupal database:query 'select * from node limit 0,1'
```
