# database:query
Ejecuta una consulta SQL directamente como argumento

**Uso:**
```
drupal database:query [arguments] [options]
dbq
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--quick | No cachear cada resultado de la query, imprimir cada fila como se reciba
--debug | Imprime información de debug, memoria y uso de CPU cuando se ejecute el programa
--html | Producir la salida en formato HTML
--xml | Producir la salida en formato XML
--raw | No se escapan los caracteres especiales en la salida del comando.
--vertical | Imprimir la salida de la query en filas verticales
--batch | Imprimir los resultados usando el tabulador como separador de columna, con cada fila en una línea nueva. Con esta opción, mysql no usa el archivo de historia

## Argumentos disponibles
Argumento | Detalles
---------|-------------
query | La consulta SQL a ejecutar
database | Clave de la base de datos en el settings.php

## Ejemplos
* Ejecutar una consulta SQL
```
drupal database:query 'select * from node limit 0,1'
```
