# config:diff
Sortida dels elements de configuració diferents a la configuració activa comparada amb un directori.

**Ús:**
```
drupal config:diff [arguments] [options]
cdi
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--reverse | Veure canvis invertits (p.e compara un directori amb la configuració activa).

## Arguments disponibles
Argument | Detalls
---------|-------------
directory | Directori amb el que comparar. Si s'omet, es tria des dels directoris de configuració de Drupal.

## Exemples
* Provide a config directory
```
drupal config:diff ../config/path
```
