# database:dump
डंप संरचना और MYSQL का कंटेंट डेटाबेसेस और टेबल्स

**Usage:**
```
drupal database:dump [arguments] [options]
dbdu
```

## Available options
Option | Details
-------|-------------
--file | अपने डेटाबेस बैकअप के लिए फ़ाइल नाम
--gz | Pass this option if you want the sql result file gzipped

## Available arguments
Argument | Details
---------|-------------
database | Settings.php से डाटाबेस कुंजी

## Examples
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
