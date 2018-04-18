# migrate:execute
Execută o migraţie disponibilă pentru aplicaţie

**Usage:**
```
drupal migrate:execute [arguments] [options]
mie
```

## Available options
Option | Details
-------|-------------
--site-url | URL-ul sitului
--db-type | commands.migrate.execute.migrations.options.db-type
--db-host | Gazda bazei de date
--db-name | Numele bazei de date
--db-user | Utilizatorul bazei de date
--db-pass | Parola bazei de date
--db-prefix | Prefixul bazei de date
--db-port | Portul bazei de date
--exclude | ID-urile migraţiilor care vor fi excluse.
--source-base_path | Local file directory containing your source site (e.g. /var/www/docroot), or your site address (for example http://example.com)

## Available arguments
Argument | Details
---------|-------------
migration-ids | Id-ul migraţiei
