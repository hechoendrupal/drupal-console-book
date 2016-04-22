# config:override
Az aktív konfiguráció értékének felülbírálása.

**Használat:**
```
$ drupal config:override [arguments]
```

## Rendelkezésre álló argumentumok
Argumentum | Részletek
---------|-------------
config-name | A konfiguráció neve.
key | Kulcs
value | Érték

## Példák
* A Contact modul elárasztási korlátjának beállítása 10 értékre.
```
$ drupal config:override contact.settings flood.limit 10
```
