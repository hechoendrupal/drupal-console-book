# migrate:execute
अनुप्रयोग के उपलब्ध माइग्रेशन को चलाएं

**application.gitbook.messages.usage:**
```
drupal migrate:execute [arguments] [options]
mie
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--site-url | साइट स्रोत URL
--db-type | commands.migrate.setup.migrations.options.db-type
--db-host | मेजबान डेटाबेस
--db-name | डेटाबेस का नाम
--db-user | डेटाबेस उपयोगकर्ता
--db-pass | डेटाबेस पासवर्ड
--db-prefix | डेटाबेस उपसर्ग
--db-port | डेटाबेस पोर्ट
--exclude | वर्जित किये गए माइग्रेशन क्रमांक
--source-base_path | commands.migrate.execute.options.source-base-path

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
migration-ids | माइग्रेशन क्रमांक
