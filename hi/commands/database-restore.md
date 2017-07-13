# database:restore
MYSQL डाटाबेस और टेबल्स ले कंटेंट और संरचना को रिस्टोर करे

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:restore [arguments] [options]
$ dbr  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--file | अपने डेटाबेस बैकअप फ़ाइल के लिए फ़ाइल नाम

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
database | Settings.php से डाटाबेस कुंजी

## commands.generate.doc.gitbook.messages.examples
* Restore the database file dump to the database default or another one specified
```
$ drupal database:restore \
  --file='/srv/dump/db.sql'

```
