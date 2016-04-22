# migrate:execute
अनुप्रयोग के उपलब्ध माइग्रेशन को चलाएं

**प्रयोग:**
```
$ drupal migrate:execute [arguments] [options]
$ mie  
```

## उपलब्ध विकल्प
विकल्प | विवरण
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

## उपलब्ध तर्कों
तर्क | विवरण
---------|-------------
migration-ids | माइग्रेशन क्रमांक
