# database:restore
MYSQL डाटाबेस और टेबल्स ले कंटेंट और संरचना को रिस्टोर करे

**application.gitbook.messages.usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file | अपने डेटाबेस बैकअप फ़ाइल के लिए फ़ाइल नाम

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Settings.php से डाटाबेस कुंजी

## application.gitbook.messages.examples
* Restore the database file dump to the database default or another one specified
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
