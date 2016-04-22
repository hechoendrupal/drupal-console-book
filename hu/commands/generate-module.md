# generate:module
Modul létrehozása.

**Használat:**
```
$ drupal generate:module [options]
$ gm  
```

## Rendelkezésre álló beállítások
Beállítás | Részletek
-------|-------------
--module | A modul neve
--machine-name | A programok által használt név (csak kisbetűk és aláhúzás)
--module-path | A modul útvonala
--description | A modul leírása
--core | Drupal alaprendszer verziója
--package | Modulcsomag
--module-file | .module fájl hozzáadása
--features-bundle | Define module as feature using the given Features bundle name
--composer | composer.json fájl hozzáadása
--dependencies | Modulfüggőségek vesszővel elválasztva (pl. context, panels)
