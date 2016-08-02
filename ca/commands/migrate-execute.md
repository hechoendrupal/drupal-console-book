# migrate:execute
Executar les migracions disponibles per l'aplicació

**Ús:**
```
$ drupal migrate:execute [arguments] [options]
$ mie  
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--site-url | URL de lloc d'origen
--db-type | commands.migrate.setup.migrations.options.db-type
--db-host | Nom de l'amfitrió
--db-name | Nom de la base de dades
--db-user | Usuari de la base de dades
--db-pass | Contrasenya de la base de dades
--db-prefix | Prefix de la base de dades
--db-port | Por de la base de dades
--exclude | Identificadors(s) a excluir de la migració

## Arguments disponibles
Argument | Detalls
---------|-------------
migration-ids | Identificador(s) de la migració
