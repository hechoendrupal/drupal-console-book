# migrate:execute
Execute a migration available for application

**application.gitbook.messages.usage:**
```
drupal migrate:execute [arguments] [options]
mie
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--site-url | Site Source URL
--db-type | commands.migrate.setup.migrations.options.db-type
--db-host | Database Host
--db-name | Database Name
--db-user | Database User
--db-pass | Database Pass
--db-prefix | Database Prefix
--db-port | Database Port
--exclude | Migration id(s) to exclude
--source-base_path | Local file directory containing your source site (e.g. /var/www/docroot), or your site address (for example http://example.com)

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
migration-ids | Migration id(s)
