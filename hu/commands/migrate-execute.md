# migrate:execute
Az alkalmazáshoz elérhető költöztetés végrehajtása

**Használat:**
```
$ drupal migrate:execute [arguments] [options]
$ mie  
```

## Rendelkezésre álló beállítások
Beállítás | Részletek
-------|-------------
--site-url | Webhely forrás URL-címe
--db-type | commands.migrate.setup.migrations.options.db-type
--db-host | Adatbázis-gazdagép
--db-name | Adatbázis neve
--db-user | Adatbázis-felhasználó
--db-pass | Adatbázis jelszó
--db-prefix | Adatbázis előtag
--db-port | Adatbázis port
--exclude | Kizárandó költöztetési azonosító(k)

## Rendelkezésre álló argumentumok
Argumentum | Részletek
---------|-------------
migration-ids | Költöztetési azonosító(k)
