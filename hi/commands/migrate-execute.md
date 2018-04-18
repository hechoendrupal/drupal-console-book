# migrate:execute
अनुप्रयोग के उपलब्ध माइग्रेशन को चलाएं

**Usage:**
```
drupal migrate:execute [arguments] [options]
mie
```

## Available options
Option | Details
-------|-------------
--site-url | साइट स्रोत URL
--db-type | commands.migrate.execute.migrations.options.db-type
--db-host | मेजबान डेटाबेस
--db-name | डेटाबेस का नाम
--db-user | डेटाबेस उपयोगकर्ता
--db-pass | डेटाबेस पासवर्ड
--db-prefix | डेटाबेस उपसर्ग
--db-port | डेटाबेस पोर्ट
--exclude | वर्जित किये गए माइग्रेशन क्रमांक
--source-base_path | Local file directory containing your source site (e.g. /var/www/docroot), or your site address (for example http://example.com)

## Available arguments
Argument | Details
---------|-------------
migration-ids | माइग्रेशन क्रमांक
