# migrate:execute
Executar les migracions disponibles per l'aplicació

**Usage:**
```
drupal migrate:execute [arguments] [options]
mie
```

## Available options
Option | Details
-------|-------------
--site-url | URL de lloc d'origen
--db-type | commands.migrate.execute.migrations.options.db-type
--db-host | Nom de l'amfitrió
--db-name | Nom de la base de dades
--db-user | Usuari de la base de dades
--db-pass | Contrasenya de la base de dades
--db-prefix | Prefix de la base de dades
--db-port | Por de la base de dades
--exclude | Identificadors(s) a excluir de la migració
--source-base_path | Local file directory containing your source site (e.g. /var/www/docroot), or your site address (for example http://example.com)

## Available arguments
Argument | Details
---------|-------------
migration-ids | Identificador(s) de la migració
