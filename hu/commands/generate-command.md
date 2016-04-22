# generate:command
Parancsok létrehozása a konzolhoz.

**Használat:**
```
$ drupal generate:command [options]
$ gcm  
```

## Rendelkezésre álló beállítások
Beállítás | Részletek
-------|-------------
--module | A modul neve.
--class | A parancsot leíró osztály. (A 'Command' szóra kell végződnie).
--name | A parancs neve.
--container-aware | A parancs ismeri-e a drupal telepítési helyét a végrehajtáskor
