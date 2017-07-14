# database:restore
MYSQL डाटाबेस और टेबल्स ले कंटेंट और संरचना को रिस्टोर करे

**Usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## Available options
Option | Details
-------|-------------
--file | अपने डेटाबेस बैकअप फ़ाइल के लिए फ़ाइल नाम

## Available arguments
Argument | Details
---------|-------------
database | Settings.php से डाटाबेस कुंजी

## Examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
