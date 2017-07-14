# database:dump
डंप संरचना आणि डेटाबेसची सामग्री.

**application.gitbook.messages.usage:**
```
drupal database:dump [arguments] [options]
dbdu
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file | आपल्या डेटाबेस बॅकअपसाठी फाइलनाव.
--gz | जर तुम्हाला हवे असेल तर एससीएल रिझल्ट फाइल gzipped

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Settings.php पासून डेटाबेस की.

## application.gitbook.messages.examples
* डिफॉल्ट डेटाबेस किंवा वितर्क वर निर्दिष्ट केलेले डेटा डंप करा.
```
drupal database:dump \
  <database>
```
* Gz संकुचित स्वरूपात डंप करा.
```
drupal database:dump \
  --gz
```
