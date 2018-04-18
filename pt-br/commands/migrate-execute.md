# migrate:execute
Execute a migration available for application

**Utilização:**
```
drupal migrate:execute [arguments] [options]
mie
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--site-url | Site Source URL
--db-type | commands.migrate.execute.migrations.options.db-type
--db-host | Database Host
--db-name | Database Name
--db-user | Database User
--db-pass | Database Pass
--db-prefix | Database Prefix
--db-port | Database Port
--exclude | Migration id(s) to exclude
--source-base_path | Local file directory containing your source site (e.g. /var/www/docroot), or your site address (for example http://example.com)

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
migration-ids | Migration id(s)
