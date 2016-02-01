# cache:rebuild
El comandament **cache:rebuild** executa Reconstrueix i esborra tota la memòria cau (cache) del lloc web.

**Ús:**
```
$ drupal cache:rebuild [arguments] 
$ cr  
```

## Arguments disponibles
Argument | Detalls
---------|-------------
cache | Esborrar una memòria cau (cache) específica.

## Exemples
* Reconstruir tota la memòria cau.
```
$ drupal cr all
```
* Reconstruir la memòria cau "discovery"
```
$ drupal cr discovery
```
