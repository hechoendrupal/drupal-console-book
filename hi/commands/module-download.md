# module:download
मोड्यूल या मोड्यूलो को डाउनलोड करें

**Usage:**
```
drupal module:download [arguments] [options]
mod
```

## Available options
Option | Details
-------|-------------
--path | The path of the contrib project
--latest | डिफ़ॉल्ट नवीनतम संस्करण डाउनलोड करने के लिए
--composer | कंपोजर का उपयोग कर मॉड्यूल डाउनलोड करें
--unstable | Module unstable

## Available arguments
Argument | Details
---------|-------------
module | मॉड्यूल या मॉड्यूलस सक्षम होने के लिए एक स्पेस से सेपरेट किया जाना चाहिए

## Examples
* Download module specifying module name and its path
```
drupal module:download  modulename  \
  --path="modules/contrib"
```
