# migrate:execute
Execută o migraţie disponibilă pentru aplicaţie

**Folosire:**
```
$ drupal migrate:execute [arguments] [options]
$ mie  
```

## Opțiuni disponibile
Opțiune | Detalii
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

## Argumente disponibile
Argument | Detalii
---------|-------------
migration-ids | Id-ul migraţiei
