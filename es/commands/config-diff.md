# config:diff
El comando **config:diff** Ouput configuration items that are different in active configuration compared with a directory.

**Uso:**
```
$ drupal config:diff [arguments] [options] 
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--reverse | See the changes in reverse (i.e diff a directory to the active configuration).

## Argumentos disponibles
Argumento | Detalles
---------|-------------
directory | The directory to diff against. If ommitted, choose from Drupal config directories.
