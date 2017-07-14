# database:restore
संरचना आणि डेटाबेसची सामग्री पुनर्संचयित करा.

**Usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## Available options
Option | Details
-------|-------------
--file | आपल्या डेटाबेस बॅकअप फाइलसाठी फाइलनाव.

## Available arguments
Argument | Details
---------|-------------
database | Settings.php पासून डेटाबेस की.

## Examples
* डेटाबेस डीफॉल्टमध्ये डेटाबेस फाइल डंप किंवा अन्य निर्दिष्ट केलेल्या.
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
