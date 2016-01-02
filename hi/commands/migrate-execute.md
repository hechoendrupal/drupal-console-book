# migrate:execute
The **migrate:execute** command अनुप्रयोग के उपलब्ध प्रवसन को चलाएं

**Usage:**
```
$ drupal migrate:execute [arguments] [options] 
$ mie  
```

## Available options
Option | Details
-------|-------------
--site-url | साइट स्रोत URL
--db-type | commands.migrate.setup.migrations.options.db-type
--db-host | मेजबान डेटाबेस
--db-name | डेटाबेस का नाम
--db-user | डेटाबेस उपयोगकर्ता
--db-pass | डेटाबेस पासवर्ड
--db-prefix | डेटाबेस उपसर्ग
--db-port | डेटाबेस पोर्ट
--exclude | वर्जित किये गए प्रवसन क्रमांक

## Available arguments
Argument | Details
---------|-------------
migration-ids | प्रवसन क्रमांक
