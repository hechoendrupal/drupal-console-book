# database:query
Ejecuta una sentencia SQL directamente como argumento

**application.gitbook.messages.usage:**
```
drupal database:query [arguments] [options]
dbq
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--quick | No cachear cada resultado de query, imprimir cada fila como se recive
--debug | Imprime información de debug, memoria y estaísticas de uso de CPU
--html | Produce un resultado en formato HTML
--xml | Produce un resultado en formato XML
--raw | No se escapan los caracteres especiales en la salida.
--vertical | Imprimir el las filas del resultado de la query verticalmente
--batch | Imprimir los resultados usando el tabulador como separador de columnas, con cada fila en una nueva línea. Con esta opción mysql no usa el archivo de historia

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
query | La sentencia SQL que será ejecutada
database | Base de datos en el settings.php

## application.gitbook.messages.examples
* Send a database query
```
drupal database:query 'select * from node limit 0,1'
```
