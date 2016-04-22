# config:diff
Az aktív konfigurációt egy könyvtárral összehasonlítva az eltérő konfigurációs elemek.

**Használat:**
```
$ drupal config:diff [arguments] [options]
```

## Rendelkezésre álló beállítások
Beállítás | Részletek
-------|-------------
--reverse | Módosítások megtekintése fordítva (vagyis egy könyvtár összehasonlítása az aktív konfigurációval).

## Rendelkezésre álló argumentumok
Argumentum | Részletek
---------|-------------
directory | A könyvtár, amivel az összehasonlítást végezni kell. Ha nincs megadva, akkor a program a Drupal konfigurációs könyvtárakból választ.
