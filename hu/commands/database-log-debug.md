# database:log:debug
Az alkalmazás aktuális naplóeseményeinek megjelenítése

**Használat:**
```
$ drupal database:log:debug [arguments] [options]
```

## Rendelkezésre álló beállítások
Beállítás | Részletek
-------|-------------
--type | Események szűrése típus alapján
--severity | Események szűrése súlyossági szintjük alapján
--user-id | Események szűrése felhasználói azonosító alapján
--asc | List events in ascending order
--limit | Egy adott számra korlátozza a találatok számát
--offset | Egy korlát kezdőpontja

## Rendelkezésre álló argumentumok
Argumentum | Részletek
---------|-------------
event-id | DBLog eseményazonosító
