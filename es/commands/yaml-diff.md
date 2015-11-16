# yaml:diff
commands.generate.doc.gitbook.messages.command_description

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal yaml:diff [arguments] [options] 
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--stats | Print statistics about YAML files comparation
--negate | Definir el modo de la comparación (diferencia o igualdad), valores posibles son TRUE/FALSE o 0/1
--limit | Limitar resultados a un número específico
--offset | Punto de empiece del límite

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
yaml-left | Fichero YAML base para comparar
yaml-right | Fichero YAML en el que determinar carencias o diferencias comparado con el archivo base YAML
