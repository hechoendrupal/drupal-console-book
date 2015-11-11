# yaml:diff
El comando **yaml:diff** Compara dos archivos YAML para encontrar las diferencias entre ambos

**Uso:**
```
$ drupal yaml:diff [arguments] [options] 
```

## Opciones disponibles
Opciones disponibles | Detalles
-------|-------------
--negate | Definir el modo de la comparación (diferencia o igualdad), valores posibles son TRUE/FALSE o 0/1
--limit | Limitar resultados a un número específico
--offset | Punto de empiece del límite

## Argumentos disponibles
Argumento | Detalles
---------|-------------
yaml-left | Fichero YAML base para comparar
yaml-right | Fichero YAML en el que determinar carencias o diferencias comparado con el archivo base YAML
