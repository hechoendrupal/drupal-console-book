# migrate:execute
Execută o migraţie disponibilă pentru aplicaţie

**application.gitbook.messages.usage:**
```
drupal migrate:execute [arguments] [options]
mie
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--site-url | URL-ul sitului
--db-type | commands.migrate.setup.migrations.options.db-type
--db-host | Gazda bazei de date
--db-name | Numele bazei de date
--db-user | Utilizatorul bazei de date
--db-pass | Parola bazei de date
--db-prefix | Prefixul bazei de date
--db-port | Portul bazei de date
--exclude | ID-urile migraţiilor care vor fi excluse.
--source-base_path | commands.migrate.execute.options.source-base-path

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
migration-ids | Id-ul migraţiei
