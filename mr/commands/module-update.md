# module:update
अनुप्रयोग मध्ये अद्यतन कोर, मॉड्यूल किंवा मॉड्यूल्स.

**Usage:**
```
drupal module:update [arguments] [options]
moup
```

## Available options
Option | Details
-------|-------------
--composer | Composer वापरून मॉड्यूल अद्यतनित करा.
--simulate | Composer सह अद्ययावत प्रक्रियेचे अनुकरण करा.

## Available arguments
Argument | Details
---------|-------------
module | अद्ययावत करण्यासाठी मॉड्यूल किंवा मॉड्यूल्सना स्पेसद्वारे विभक्त व्हायला हवे. कोर अद्यतनित करण्यासाठी रिक्त सोडा आणि Composer द्वारे व्यवस्थापित केलेले आपले सर्व मॉड्यूल.

## Examples
* Update module specifying module name and composer parameter
```
drupal module:update  modulename  \
  --composer
```
