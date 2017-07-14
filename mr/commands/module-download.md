# module:download
अर्ज मॉड्यूल किंवा मॉड्यूल डाउनलोड करा.

**Usage:**
```
drupal module:download [arguments] [options]
mod
md
```

## Available options
Option | Details
-------|-------------
--path | Contrib प्रकल्प मार्ग.
--latest | सर्वात अलीकडील आवृत्ती डाउनलोड करण्यासाठी डीफॉल्ट.
--composer | Composer वापरून मॉड्यूल डाउनलोड करा.
--unstable | commands.module.install.options.unstable

## Available arguments
Argument | Details
---------|-------------
module | सक्षम केलेल्या मोड्यूल किंवा मॉड्यूल्सना स्पेसद्वारे विभक्त व्हायला हवे.

## Examples
* Download module specifying module name and its path
```
drupal module:download  modulename  \
  --path="modules/contrib"
```
