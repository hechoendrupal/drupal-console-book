# config:diff
El comandament **config:diff** executa Ouput configuration items that are different in active configuration compared with a directory.

**Ús:**
```
$ drupal config:diff [arguments] [options] 
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--reverse | See the changes in reverse (i.e diff a directory to the active configuration).

## Arguments disponibles
Argument | Detalls
---------|-------------
directory | The directory to diff against. If ommitted, choose from Drupal config directories.
