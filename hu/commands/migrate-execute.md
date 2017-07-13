# migrate:execute
Az alkalmazáshoz elérhető költöztetés végrehajtása

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal migrate:execute [arguments] [options]
$ mie  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
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

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
migration-ids | Költöztetési azonosító(k)
