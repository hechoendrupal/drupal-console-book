# migrate:execute
The **migrate:execute** command Az alkalmazáshoz elérhető költöztetés végrehajtása

**Usage:**
```
$ drupal migrate:execute [arguments] [options] 
$ mie  
```

## Available options
Option | Details
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

## Available arguments
Argument | Details
---------|-------------
migration-ids | Költöztetési azonosító(k)
