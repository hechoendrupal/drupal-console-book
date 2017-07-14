# migrate:execute
Exécute une migration disponible dans l'application

**application.gitbook.messages.usage:**
```
drupal migrate:execute [arguments] [options]
mie
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--site-url | Url source du site
--db-type | commands.migrate.setup.migrations.options.db-type
--db-host | Serveur de la base de données
--db-name | Nom de la base de données
--db-user | Utilisateur de la base de données
--db-pass | Mot de passe de la base de données
--db-prefix | Préfixe de la base de données
--db-port | Port de la base de données
--exclude | Id(s) de migration à exclure
--source-base_path | commands.migrate.execute.options.source-base-path

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
migration-ids | Id de migration
