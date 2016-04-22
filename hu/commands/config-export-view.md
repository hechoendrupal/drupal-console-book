# config:export:view
Nézet exportálása YAML-formátumban egy megadott modulba, hogy újra lehessen használni más weboldalon.

**Használat:**
```
$ drupal config:export:view [arguments] [options]
$ cev  
```

## Rendelkezésre álló beállítások
Beállítás | Részletek
-------|-------------
--module | A modul neve.
--optional-config | Nézet exportálása a modulba nem kötelező YAML-konfigurációként
--include-module-dependencies | Modulfüggőségeinek tartalmazása a modul info.yml fájljában

## Rendelkezésre álló argumentumok
Argumentum | Részletek
---------|-------------
view-id | Nézet azonosítója
