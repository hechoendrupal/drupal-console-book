# migrate:execute
अनुप्रयोगासाठी उपलब्ध स्थलांतरित करा.

**Usage:**
```
drupal migrate:execute [arguments] [options]
mie
```

## Available options
Option | Details
-------|-------------
--site-url | साइट स्त्रोत URL.
--db-type | commands.migrate.setup.migrations.options.db-type
--db-host | डेटाबेस यजमान.
--db-name | डेटाबेस नाव.
--db-user | डेटाबेस वापरकर्ता.
--db-pass | डेटाबेस पास.
--db-prefix | डेटाबेस उपसर्ग.
--db-port | डेटाबेस हस्तांतरण.
--exclude | वगळण्यासाठी स्थलांतरण आयडी.
--source-base_path | Local file directory containing your source site (e.g. /var/www/docroot), or your site address (for example http://example.com)

## Available arguments
Argument | Details
---------|-------------
migration-ids | स्थलांतरण आयडी.
