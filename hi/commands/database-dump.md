# database:dump
डंप संरचना और MYSQL का कंटेंट डेटाबेसेस और टेबल्स

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:dump [arguments] [options]
$ dbdu  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--file | अपने डेटाबेस बैकअप के लिए फ़ाइल नाम
--gz | Pass this option if you want the sql result file gzipped

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
database | Settings.php से डाटाबेस कुंजी

## commands.generate.doc.gitbook.messages.examples
* Dump default database or the one specified on the argument
```
$ drupal database:dump \
  <database>
```
* Dump in gz compressed format
```
$ drupal database:dump \
  --gz
```
