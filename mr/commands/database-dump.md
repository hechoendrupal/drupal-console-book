# database:dump
डंप संरचना आणि डेटाबेसची सामग्री.

**Usage:**
```
drupal database:dump [arguments] [options]
dbdu
```

## Available options
Option | Details
-------|-------------
--file | आपल्या डेटाबेस बॅकअपसाठी फाइलनाव.
--gz | जर तुम्हाला हवे असेल तर एससीएल रिझल्ट फाइल gzipped

## Available arguments
Argument | Details
---------|-------------
database | Settings.php पासून डेटाबेस की.

## Examples
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
