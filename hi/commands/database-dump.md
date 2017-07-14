# database:dump
डंप संरचना और MYSQL का कंटेंट डेटाबेसेस और टेबल्स

**application.gitbook.messages.usage:**
```
drupal database:dump [arguments] [options]
dbdu
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file | अपने डेटाबेस बैकअप के लिए फ़ाइल नाम
--gz | Pass this option if you want the sql result file gzipped

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Settings.php से डाटाबेस कुंजी

## application.gitbook.messages.examples
* Dump default database or the one specified on the argument
```
drupal database:dump \
  <database>
```
* Dump in gz compressed format
```
drupal database:dump \
  --gz
```
