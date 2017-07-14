# database:restore
संरचना आणि डेटाबेसची सामग्री पुनर्संचयित करा.

**application.gitbook.messages.usage:**
```
drupal database:restore [arguments] [options]
dbr
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file | आपल्या डेटाबेस बॅकअप फाइलसाठी फाइलनाव.

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Settings.php पासून डेटाबेस की.

## application.gitbook.messages.examples
* डेटाबेस डीफॉल्टमध्ये डेटाबेस फाइल डंप किंवा अन्य निर्दिष्ट केलेल्या.
```
drupal database:restore \
  --file='/srv/dump/db.sql'
```
