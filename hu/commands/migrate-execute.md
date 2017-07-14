# migrate:execute
Az alkalmazáshoz elérhető költöztetés végrehajtása

**application.gitbook.messages.usage:**
```
drupal migrate:execute [arguments] [options]
mie
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
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
--source-base_path | commands.migrate.execute.options.source-base-path

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
migration-ids | Költöztetési azonosító(k)
