# migrate:execute
El comandament **migrate:execute** executa Executar la migració disponible per l'aplicació

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
--db-host | Nom del host
--db-name | Nom de la base de dades
--db-user | Usuari de la base de dades
--db-pass | COntrasenya de la base de dades
--db-prefix | Prefix de la base de dades
--db-port | Por de la base de dades
--exclude | Id(s) a excluir de la migració

## Arguments disponibles
Argument | Detalls
---------|-------------
migration-ids | Id(s) de la migració
