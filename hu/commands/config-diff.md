# config:diff
Az aktív konfigurációt egy könyvtárral összehasonlítva az eltérő konfigurációs elemek.

**Usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## Available options
Option | Details
-------|-------------
--reverse | Módosítások megtekintése fordítva (vagyis egy könyvtár összehasonlítása az aktív konfigurációval).

## Available arguments
Argument | Details
---------|-------------
directory | A könyvtár, amivel az összehasonlítást végezni kell. Ha nincs megadva, akkor a program a Drupal konfigurációs könyvtárakból választ.

## Examples
* Provide a config directory
```
drupal config:diff ../config/path
```
