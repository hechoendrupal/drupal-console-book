# config:diff
Sortida dels elements de configuració diferents a la configuració activa comparada amb un directori.

**Usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## Available options
Option | Details
-------|-------------
--reverse | Veure canvis invertits (p.e compara un directori amb la configuració activa).

## Available arguments
Argument | Details
---------|-------------
directory | Directori amb el que comparar. Si s'omet, es tria des dels directoris de configuració de Drupal.

## Examples
* Provide a config directory
```
drupal config:diff ../config/path
```
